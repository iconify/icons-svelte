<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo6vdfyxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo6vdfyxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cupcake" {...props}></Icon>
