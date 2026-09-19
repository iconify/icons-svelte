<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjbv_7boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="sjbv_7boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-index-duo" {...props}></Icon>
