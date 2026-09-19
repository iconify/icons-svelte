<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry1z8robp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry1z8robp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:gear" {...props}></Icon>
