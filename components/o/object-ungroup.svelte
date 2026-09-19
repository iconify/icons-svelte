<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2t0rrxjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="p2t0rrxjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:object-ungroup" {...props}></Icon>
