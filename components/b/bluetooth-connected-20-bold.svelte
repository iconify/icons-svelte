<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3-ldu6ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h3-ldu6ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bluetooth-connected-20-bold" {...props}></Icon>
