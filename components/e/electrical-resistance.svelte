<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcvgcht7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcvgcht7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:electrical-resistance" {...props}></Icon>
