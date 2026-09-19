<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl1s8xrfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xl1s8xrfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-route-outline" {...props}></Icon>
