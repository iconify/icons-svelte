<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk8zpy4cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk8zpy4cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-big-up-dash" {...props}></Icon>
