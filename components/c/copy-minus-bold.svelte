<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry6677b8a.css';
import '../../css/n/nazq8_bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry6677b8a"/><path class="nazq8_bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-minus-bold" {...props}></Icon>
