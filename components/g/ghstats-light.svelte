<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmxj07brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmxj07brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghstats-light" {...props}></Icon>
