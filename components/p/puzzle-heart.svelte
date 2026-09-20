<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm1y5sbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm1y5sbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-heart" {...props}></Icon>
