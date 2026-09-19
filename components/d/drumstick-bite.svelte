<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am2xe984g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="am2xe984g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:drumstick-bite" {...props}></Icon>
