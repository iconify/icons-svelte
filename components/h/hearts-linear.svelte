<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sty21ibsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sty21ibsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hearts-linear" {...props}></Icon>
