<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9y09mbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="m9y09mbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclamation-bold" {...props}></Icon>
