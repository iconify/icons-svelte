<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir5lyl61v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ir5lyl61v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:o-square" {...props}></Icon>
