<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw46o2y3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hw46o2y3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-double-stroke-12" {...props}></Icon>
