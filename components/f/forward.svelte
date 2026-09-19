<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td2eli6nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="td2eli6nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:forward" {...props}></Icon>
