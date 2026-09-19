<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km5ljjbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="km5ljjbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bed-empty" {...props}></Icon>
