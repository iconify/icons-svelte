<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi1p6ucli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gi1p6ucli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset-duo" {...props}></Icon>
