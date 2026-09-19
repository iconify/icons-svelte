<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl54b9bcm.css';
import '../../css/o/oy01ueb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl54b9bcm"/><path class="oy01ueb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:calendar" {...props}></Icon>
