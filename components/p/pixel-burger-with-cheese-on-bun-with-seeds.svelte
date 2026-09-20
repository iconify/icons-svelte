<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq3zy8b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fq3zy8b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-burger-with-cheese-on-bun-with-seeds" {...props}></Icon>
