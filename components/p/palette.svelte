<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0yp2jb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i0yp2jb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:palette" {...props}></Icon>
