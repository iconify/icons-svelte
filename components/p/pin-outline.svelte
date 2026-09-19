<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq8vbjr1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vq8vbjr1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pin-outline" {...props}></Icon>
