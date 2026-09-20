<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiqihmufh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiqihmufh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-distribute-center" {...props}></Icon>
