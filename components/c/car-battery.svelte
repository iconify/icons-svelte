<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_w53ebqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_w53ebqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:car-battery" {...props}></Icon>
