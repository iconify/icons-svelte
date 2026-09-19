<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5o5hyb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5o5hyb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-dot" {...props}></Icon>
