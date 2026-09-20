<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqrv59bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dqrv59bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iobroker-dark" {...props}></Icon>
