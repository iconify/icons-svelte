<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp0ezjbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mp0ezjbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hexagon-nodes" {...props}></Icon>
