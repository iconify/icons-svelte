<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihf3etbjh.css';
import '../../css/p/ph2qz-bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ihf3etbjh"/><path class="ph2qz-bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:alarm" {...props}></Icon>
