<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvepzhy6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rvepzhy6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:brave-reverse" {...props}></Icon>
