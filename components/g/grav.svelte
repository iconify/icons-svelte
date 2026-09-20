<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4_iznb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q4_iznb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grav" {...props}></Icon>
