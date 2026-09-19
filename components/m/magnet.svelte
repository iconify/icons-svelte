<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mec9fr0sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mec9fr0sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:magnet" {...props}></Icon>
