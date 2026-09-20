<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tol6492tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tol6492tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-off" {...props}></Icon>
