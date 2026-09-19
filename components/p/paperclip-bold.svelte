<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhh2ycz5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="nhh2ycz5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:paperclip-bold" {...props}></Icon>
