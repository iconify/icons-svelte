<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo9elgb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vo9elgb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:restroom" {...props}></Icon>
