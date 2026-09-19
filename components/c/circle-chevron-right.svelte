<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfcq_3b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfcq_3b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-chevron-right" {...props}></Icon>
