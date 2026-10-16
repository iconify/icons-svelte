<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hosli1blv.css';
import '../../css/u/uoh_r3_bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hosli1blv"/><path class="uoh_r3_bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-snooze-48" {...props}></Icon>
