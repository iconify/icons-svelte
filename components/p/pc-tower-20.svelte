<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb6fqqb0z.css';
import '../../css/u/u8f88948k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jb6fqqb0z"/><path class="u8f88948k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pc-tower-20" {...props}></Icon>
