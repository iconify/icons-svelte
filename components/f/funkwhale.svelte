<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in4fcbbhz.css';
import '../../css/d/dellb70ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in4fcbbhz"/><path class="dellb70ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:funkwhale" {...props}></Icon>
