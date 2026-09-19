<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2jx_csvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1632};
const content = `<path class="u2jx_csvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:rocket" {...props}></Icon>
