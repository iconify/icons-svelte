<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv6bx_bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sv6bx_bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lips-bold" {...props}></Icon>
