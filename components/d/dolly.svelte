<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd_q8ew-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nd_q8ew-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dolly" {...props}></Icon>
