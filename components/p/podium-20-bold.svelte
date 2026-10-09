<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-6jetbog.css';
import '../../css/h/hbbf6bc_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h-6jetbog"/><path class="hbbf6bc_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:podium-20-bold" {...props}></Icon>
