<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx0iropur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rx0iropur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclamation-duo" {...props}></Icon>
