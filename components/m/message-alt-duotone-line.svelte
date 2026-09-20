<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr4c9lt1j.css';
import '../../css/l/lp5zebcnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="rr4c9lt1j"/><path class="lp5zebcnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:message-alt-duotone-line" {...props}></Icon>
