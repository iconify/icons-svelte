<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg5z9hj3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gg5z9hj3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chart-area" {...props}></Icon>
