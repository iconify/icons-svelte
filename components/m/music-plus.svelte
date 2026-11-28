<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/couo1tbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="couo1tbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:music-plus" {...props}></Icon>
