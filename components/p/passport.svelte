<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4_hapb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="q4_hapb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:passport" {...props}></Icon>
