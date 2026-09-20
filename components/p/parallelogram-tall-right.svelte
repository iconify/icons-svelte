<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaz2rfbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xaz2rfbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parallelogram-tall-right" {...props}></Icon>
