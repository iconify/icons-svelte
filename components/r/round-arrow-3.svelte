<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk8mt4fmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8mt4fmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:round-arrow-3" {...props}></Icon>
