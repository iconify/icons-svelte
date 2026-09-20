<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq2lc6yth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aq2lc6yth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:iobroker-light" {...props}></Icon>
