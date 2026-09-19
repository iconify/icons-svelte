<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy2zf99lb.css';
import '../../css/t/tf5xj-bsz.css';
import '../../css/k/koofvxt_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fy2zf99lb"/><circle class="tf5xj-bsz"/><circle class="koofvxt_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:car-outline" {...props}></Icon>
