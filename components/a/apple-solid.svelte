<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoel_3brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoel_3brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:apple-solid" {...props}></Icon>
