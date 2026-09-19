<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp8hlbcad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="vp8hlbcad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:oil-well" {...props}></Icon>
