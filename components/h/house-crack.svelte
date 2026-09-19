<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abb0r1czz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="abb0r1czz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-crack" {...props}></Icon>
