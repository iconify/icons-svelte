<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7c98za8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="o7c98za8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-1" {...props}></Icon>
