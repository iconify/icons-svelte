<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cos1jybps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cos1jybps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:minimize-fill-12" {...props}></Icon>
