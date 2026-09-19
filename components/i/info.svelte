<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0rokl91k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m0rokl91k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:info" {...props}></Icon>
