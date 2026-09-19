<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lryjw4fpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lryjw4fpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:line" {...props}></Icon>
