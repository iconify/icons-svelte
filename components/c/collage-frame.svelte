<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_e13acxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_e13acxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:collage-frame" {...props}></Icon>
