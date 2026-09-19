<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2_yd-19i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y2_yd-19i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cog-1-duo" {...props}></Icon>
