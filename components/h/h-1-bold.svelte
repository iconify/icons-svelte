<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh8bllbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rh8bllbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-1-bold" {...props}></Icon>
