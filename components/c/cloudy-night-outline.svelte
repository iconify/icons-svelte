<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4ylmckef.css';
import '../../css/h/htohhkvke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f4ylmckef"/><path class="htohhkvke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloudy-night-outline" {...props}></Icon>
