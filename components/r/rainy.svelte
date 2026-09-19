<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiimmlbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oiimmlbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:rainy" {...props}></Icon>
