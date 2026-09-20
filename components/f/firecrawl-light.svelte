<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2_fj7bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":72};
const content = `<path class="d2_fj7bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:firecrawl-light" {...props}></Icon>
