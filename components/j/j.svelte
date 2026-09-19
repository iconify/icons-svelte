<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx31dgbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cx31dgbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:j" {...props}></Icon>
