<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lstoyk0re.css';
import '../../css/s/s4l_bwbwm.css';
import '../../css/x/x5tz2lbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lstoyk0re"/><path class="s4l_bwbwm"/><path class="x5tz2lbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:letter-spacing-48-bold" {...props}></Icon>
