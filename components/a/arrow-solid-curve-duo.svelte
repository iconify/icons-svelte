<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr4wmez8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pr4wmez8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-curve-duo" {...props}></Icon>
