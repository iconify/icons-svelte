<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pshj70bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pshj70bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bookheaven-light" {...props}></Icon>
