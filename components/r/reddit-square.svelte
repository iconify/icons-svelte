<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll__7fb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ll__7fb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:reddit-square" {...props}></Icon>
