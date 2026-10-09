<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h82f8zb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h82f8zb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hexagon-20" {...props}></Icon>
