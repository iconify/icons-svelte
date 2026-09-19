<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaslocbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaslocbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:ellipse" {...props}></Icon>
