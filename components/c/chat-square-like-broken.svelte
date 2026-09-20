<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ay49rbbdp.css';
import '../../css/r/rc_eaccxy.css';
import '../../css/e/ejdkgccas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ay49rbbdp"/><path class="rc_eaccxy"/><path class="ejdkgccas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-like-broken" {...props}></Icon>
