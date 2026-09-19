<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_-085zbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="g_-085zbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:2-square" {...props}></Icon>
