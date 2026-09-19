<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp4eqjvst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="mp4eqjvst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hourglass-start" {...props}></Icon>
