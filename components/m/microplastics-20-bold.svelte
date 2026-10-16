<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_hvfxj7d.css';
import '../../css/q/q7snb2uzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s_hvfxj7d"/><path class="q7snb2uzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microplastics-20-bold" {...props}></Icon>
