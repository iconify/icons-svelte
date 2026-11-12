<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp1h2bbup.css';
import '../../css/d/d8smgqcqm.css';
import '../../css/k/k4ph6mujc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xp1h2bbup"/><path class="d8smgqcqm"/><path class="k4ph6mujc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ente-locker-light" {...props}></Icon>
