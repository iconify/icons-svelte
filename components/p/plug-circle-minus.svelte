<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l82wo8b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="l82wo8b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plug-circle-minus" {...props}></Icon>
