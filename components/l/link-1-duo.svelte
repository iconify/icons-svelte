<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjd-he5zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mjd-he5zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:link-1-duo" {...props}></Icon>
