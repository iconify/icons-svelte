<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htdpczpdl.css';
import '../../css/w/waf8_fo8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htdpczpdl"/><path class="waf8_fo8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-phone-call" {...props}></Icon>
