<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9-4w-bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":72};
const content = `<path class="o9-4w-bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:firecrawl-dark" {...props}></Icon>
