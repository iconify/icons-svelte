<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcimo1b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcimo1b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:axes" {...props}></Icon>
