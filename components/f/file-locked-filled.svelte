<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgf_iypbv.css';
import '../../css/s/sfsa80h7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgf_iypbv"/><path class="sfsa80h7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-locked-filled" {...props}></Icon>
