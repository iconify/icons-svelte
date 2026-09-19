<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mobnpr2vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mobnpr2vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:elementor" {...props}></Icon>
