<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnhz2ikjq.css';
import '../../css/w/wd_x4i40e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnhz2ikjq"/><path class="wd_x4i40e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-fold-filled" {...props}></Icon>
