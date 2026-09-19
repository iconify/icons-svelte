<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo7wix1lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uo7wix1lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-spine" {...props}></Icon>
