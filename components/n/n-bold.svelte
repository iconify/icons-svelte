<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rro55svmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rro55svmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:n-bold" {...props}></Icon>
