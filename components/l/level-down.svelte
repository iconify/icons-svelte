<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2pxd09sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w2pxd09sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:level-down" {...props}></Icon>
