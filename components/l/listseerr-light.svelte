<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0oi_lqlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0oi_lqlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listseerr-light" {...props}></Icon>
