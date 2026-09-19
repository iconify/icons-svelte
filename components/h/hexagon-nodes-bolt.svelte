<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbw3xobnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cbw3xobnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hexagon-nodes-bolt" {...props}></Icon>
