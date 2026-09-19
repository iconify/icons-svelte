<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blh-xxc1n.css';
import '../../css/t/t0z_rmbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="blh-xxc1n"/><path class="t0z_rmbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:microphone-filled" {...props}></Icon>
