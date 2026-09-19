<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-7-8jbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g-7-8jbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-curve" {...props}></Icon>
