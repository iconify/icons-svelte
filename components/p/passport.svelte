<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st7_mloem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="st7_mloem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:passport" {...props}></Icon>
