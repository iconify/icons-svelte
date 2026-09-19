<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_m8u_bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c_m8u_bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:die-3-bold" {...props}></Icon>
