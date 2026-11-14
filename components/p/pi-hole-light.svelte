<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk44qabdq.css';
import '../../css/j/jpd9n3d1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xk44qabdq"/><path class="jpd9n3d1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-hole-light" {...props}></Icon>
