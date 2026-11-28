<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxkr8sagi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxkr8sagi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-sun" {...props}></Icon>
