<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz3z958ur.css';
import '../../css/u/utltrjg1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uz3z958ur"/><path class="utltrjg1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:manifest-light" {...props}></Icon>
