<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-2aylgvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="y-2aylgvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-close" {...props}></Icon>
