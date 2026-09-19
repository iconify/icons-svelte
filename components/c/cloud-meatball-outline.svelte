<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji5cev1ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji5cev1ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cloud-meatball-outline" {...props}></Icon>
