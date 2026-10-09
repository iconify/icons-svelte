<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsb2-hb_n.css';
import '../../css/r/r56804bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zsb2-hb_n"/><path class="r56804bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladder-20-bold" {...props}></Icon>
