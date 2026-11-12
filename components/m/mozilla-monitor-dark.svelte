<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m18h498ob.css';
import '../../css/c/cpghrcrth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m18h498ob"/><path class="cpghrcrth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mozilla-monitor-dark" {...props}></Icon>
