<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg5a_1n1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg5a_1n1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:furry-network" {...props}></Icon>
