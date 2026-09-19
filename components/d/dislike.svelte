<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4wzdfbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h4wzdfbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:dislike" {...props}></Icon>
