<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsx8atb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rsx8atb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:building-3-bold" {...props}></Icon>
