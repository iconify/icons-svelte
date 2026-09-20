<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icfk7ac_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="icfk7ac_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:backward-step" {...props}></Icon>
