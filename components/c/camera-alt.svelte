<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hve8ghb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hve8ghb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:camera-alt" {...props}></Icon>
