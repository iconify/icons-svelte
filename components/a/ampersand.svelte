<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb2-eywbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="fb2-eywbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ampersand" {...props}></Icon>
