<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyhm1y1to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyhm1y1to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:record-mail-line" {...props}></Icon>
