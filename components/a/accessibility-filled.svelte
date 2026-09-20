<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy31_s20a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy31_s20a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:accessibility-filled" {...props}></Icon>
