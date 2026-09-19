<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/k/k55mosbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="k55mosbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pause-circle-outline" {...props}></Icon>
