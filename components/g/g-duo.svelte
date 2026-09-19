<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_c-jfbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="z_c-jfbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:g-duo" {...props}></Icon>
