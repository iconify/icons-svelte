<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyv35uw7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="fyv35uw7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:campfire" {...props}></Icon>
