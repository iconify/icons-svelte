<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p00b0weyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":150,"height":150};
const content = `<path class="p00b0weyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nx-light" {...props}></Icon>
