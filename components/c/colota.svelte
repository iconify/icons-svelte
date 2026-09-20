<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7c-2eb5a.css';
import '../../css/r/r1nvtit5z.css';
import '../../css/s/snwmkb8ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7c-2eb5a"/><path class="r1nvtit5z"/><path class="snwmkb8ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:colota" {...props}></Icon>
