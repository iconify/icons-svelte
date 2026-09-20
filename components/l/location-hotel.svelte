<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0g6m1bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f0g6m1bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:location-hotel" {...props}></Icon>
