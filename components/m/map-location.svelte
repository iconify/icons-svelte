<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrcm8ibqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="hrcm8ibqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:map-location" {...props}></Icon>
