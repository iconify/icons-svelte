<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggc7n1z-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ggc7n1z-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:j-bold" {...props}></Icon>
