<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex-oqjthi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ex-oqjthi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fog-1" {...props}></Icon>
