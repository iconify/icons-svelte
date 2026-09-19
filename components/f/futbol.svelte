<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzokasbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzokasbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:futbol" {...props}></Icon>
