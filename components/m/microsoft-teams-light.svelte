<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f34x6acyd.css';
import '../../css/s/stvmudbrq.css';
import '../../css/l/l3_nh_z-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f34x6acyd"/><path class="stvmudbrq"/><path class="l3_nh_z-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-teams-light" {...props}></Icon>
