<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgqxapb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":350,"height":44};
const content = `<path class="zgqxapb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alivecor" {...props}></Icon>
