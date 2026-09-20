<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjprgp5hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mjprgp5hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:cupcake" {...props}></Icon>
