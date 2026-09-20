<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdm2rjbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdm2rjbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:filter" {...props}></Icon>
