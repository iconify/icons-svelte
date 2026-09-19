<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0op70bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a0op70bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:location-arrow-duo" {...props}></Icon>
