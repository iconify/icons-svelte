<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ompinta_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ompinta_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-half-duo" {...props}></Icon>
