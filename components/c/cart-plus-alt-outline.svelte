<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvdz23vge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvdz23vge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cart-plus-alt-outline" {...props}></Icon>
