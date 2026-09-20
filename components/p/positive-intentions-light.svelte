<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltfp6vbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ltfp6vbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:positive-intentions-light" {...props}></Icon>
