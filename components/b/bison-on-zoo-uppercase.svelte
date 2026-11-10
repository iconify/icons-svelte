<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-774wb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y-774wb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bison-on-zoo-uppercase" {...props}></Icon>
