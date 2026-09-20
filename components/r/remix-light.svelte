<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw-9bxhcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":297};
const content = `<path class="uw-9bxhcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:remix-light" {...props}></Icon>
