<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1-q2fbul.css';
import '../../css/w/wz1m72y3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s1-q2fbul"/><path class="wz1m72y3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pin-20-bold" {...props}></Icon>
