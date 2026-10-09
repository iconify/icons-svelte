<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8maq5b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u8maq5b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-wind-20" {...props}></Icon>
