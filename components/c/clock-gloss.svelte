<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4g4k4bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4g4k4bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clock-gloss" {...props}></Icon>
