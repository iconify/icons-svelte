<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uju-xcg-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uju-xcg-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:play-duo" {...props}></Icon>
