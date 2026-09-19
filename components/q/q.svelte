<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ezqygrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="e6ezqygrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:q" {...props}></Icon>
