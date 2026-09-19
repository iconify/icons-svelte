<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnc7j12jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cnc7j12jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:code-bold" {...props}></Icon>
