<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzzdz3wvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lzzdz3wvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ieee" {...props}></Icon>
