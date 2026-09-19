<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5_5wi6ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x5_5wi6ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-external" {...props}></Icon>
