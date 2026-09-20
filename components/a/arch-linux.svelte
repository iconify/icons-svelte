<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc_mv5j_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tc_mv5j_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arch-linux" {...props}></Icon>
