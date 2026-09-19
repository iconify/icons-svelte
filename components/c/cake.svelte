<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt96rf38k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mt96rf38k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:cake" {...props}></Icon>
