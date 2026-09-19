<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj4jt58kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uj4jt58kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bench" {...props}></Icon>
