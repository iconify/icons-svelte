<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfgux_bnw.css';
import '../../css/c/cnwk2jbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rfgux_bnw"/><path class="cnwk2jbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inbox-20-bold" {...props}></Icon>
