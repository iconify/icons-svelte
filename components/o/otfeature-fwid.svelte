<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2b7a6_zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l2b7a6_zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-fwid" {...props}></Icon>
