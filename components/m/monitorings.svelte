<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyz6619jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xyz6619jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:monitorings" {...props}></Icon>
