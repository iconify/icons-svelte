<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m599ys8mi.css';
import '../../css/m/mgsi99bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m599ys8mi"/><path class="mgsi99bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car-battery" {...props}></Icon>
