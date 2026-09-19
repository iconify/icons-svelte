<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpvyesbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpvyesbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:cv" {...props}></Icon>
