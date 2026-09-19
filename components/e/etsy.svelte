<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5u_j6n2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="q5u_j6n2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:etsy" {...props}></Icon>
