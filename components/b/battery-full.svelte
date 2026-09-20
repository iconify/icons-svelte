<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op5xopbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op5xopbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery-full" {...props}></Icon>
