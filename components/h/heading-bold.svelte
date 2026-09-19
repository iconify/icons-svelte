<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7xn8x6wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a7xn8x6wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heading-bold" {...props}></Icon>
