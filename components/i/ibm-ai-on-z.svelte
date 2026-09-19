<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbr5kbcpv.css';
import '../../css/l/lckqvt-5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dbr5kbcpv"/><path class="lckqvt-5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-ai-on-z" {...props}></Icon>
