<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl_o3vrxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_o3vrxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fishing-rod" {...props}></Icon>
