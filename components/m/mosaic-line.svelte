<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zef4ti3ay.css';
import '../../css/k/k63q7xktr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zef4ti3ay"/><path class="k63q7xktr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mosaic-line" {...props}></Icon>
