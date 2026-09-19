<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1v8i60eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="l1v8i60eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pin-1" {...props}></Icon>
