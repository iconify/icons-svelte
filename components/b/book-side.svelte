<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kadhl0b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="kadhl0b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-side" {...props}></Icon>
