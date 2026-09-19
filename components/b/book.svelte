<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg9lrzmst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xg9lrzmst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book" {...props}></Icon>
