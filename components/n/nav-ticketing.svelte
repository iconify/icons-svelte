<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1o8eolcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m1o8eolcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-ticketing" {...props}></Icon>
