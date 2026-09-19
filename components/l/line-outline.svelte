<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu8kq7bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xu8kq7bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:line-outline" {...props}></Icon>
