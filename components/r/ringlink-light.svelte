<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-g18w0dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e-g18w0dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ringlink-light" {...props}></Icon>
