<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aceok0kpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="aceok0kpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-1-duo" {...props}></Icon>
