<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb6qy0bak.css';
import '../../css/q/qtm7ddo2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hb6qy0bak"/><path class="qtm7ddo2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-2000" {...props}></Icon>
