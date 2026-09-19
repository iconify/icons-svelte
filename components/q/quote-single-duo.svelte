<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlv7vxu_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rlv7vxu_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:quote-single-duo" {...props}></Icon>
