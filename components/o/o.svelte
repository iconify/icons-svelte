<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk2lrzbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xk2lrzbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:o" {...props}></Icon>
