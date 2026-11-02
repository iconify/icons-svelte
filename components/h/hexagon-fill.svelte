<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff1pz61xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff1pz61xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hexagon-fill" {...props}></Icon>
