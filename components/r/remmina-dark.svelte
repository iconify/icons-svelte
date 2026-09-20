<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0c4prb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0c4prb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:remmina-dark" {...props}></Icon>
