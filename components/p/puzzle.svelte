<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuhx3t5iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuhx3t5iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:puzzle" {...props}></Icon>
