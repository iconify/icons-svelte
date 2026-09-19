<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy5-l_xmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy5-l_xmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:icecream-alt-outline" {...props}></Icon>
