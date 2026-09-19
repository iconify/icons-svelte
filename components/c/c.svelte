<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzo4ogbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vzo4ogbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:c" {...props}></Icon>
