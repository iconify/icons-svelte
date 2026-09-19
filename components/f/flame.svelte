<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp6swmwrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp6swmwrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flame" {...props}></Icon>
