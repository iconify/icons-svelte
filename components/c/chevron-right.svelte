<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz5w6354e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jz5w6354e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-right" {...props}></Icon>
