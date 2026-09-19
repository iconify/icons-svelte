<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkkl1d7ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="vkkl1d7ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cross" {...props}></Icon>
