<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i47d-_nwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i47d-_nwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-grin-tongue-squint" {...props}></Icon>
