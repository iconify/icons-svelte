<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hye2qnbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hye2qnbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-spline-solid" {...props}></Icon>
