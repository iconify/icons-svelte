<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9uv-zbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b9uv-zbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-spread" {...props}></Icon>
