<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxu3tabzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="pxu3tabzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:filter-circle-xmark" {...props}></Icon>
