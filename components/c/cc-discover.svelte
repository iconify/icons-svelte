<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5t5z5and.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="w5t5z5and"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cc-discover" {...props}></Icon>
