<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4gcxe4mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x4gcxe4mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:puzzle-piece-duo" {...props}></Icon>
