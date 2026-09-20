<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeed0tk-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xeed0tk-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:massage" {...props}></Icon>
