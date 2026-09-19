<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy7mr6luy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vy7mr6luy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:k-outline" {...props}></Icon>
