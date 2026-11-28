<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwtloxbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwtloxbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:brick-wall" {...props}></Icon>
