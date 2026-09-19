<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-1rd3zwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="y-1rd3zwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bed-bunk" {...props}></Icon>
