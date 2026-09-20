<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4lb9fbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w4lb9fbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-chip-2" {...props}></Icon>
