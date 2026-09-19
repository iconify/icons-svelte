<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvvvaq5nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dvvvaq5nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fire-1-outline" {...props}></Icon>
