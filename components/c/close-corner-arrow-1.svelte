<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vogze0bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vogze0bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:close-corner-arrow-1" {...props}></Icon>
