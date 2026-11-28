<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0zr3cc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0zr3cc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:laptop-gear" {...props}></Icon>
