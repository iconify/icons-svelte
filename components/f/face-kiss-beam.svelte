<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-u1fdicj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-u1fdicj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-kiss-beam" {...props}></Icon>
