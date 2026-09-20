<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2pyy_bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2pyy_bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:coin-1" {...props}></Icon>
