<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl30djqpt.css';
import '../../css/a/ad8qs5b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rl30djqpt"/><path class="ad8qs5b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:brother" {...props}></Icon>
