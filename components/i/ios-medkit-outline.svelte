<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqm3cru9o.css';
import '../../css/u/up_x2juwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqm3cru9o"/><path class="up_x2juwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-medkit-outline" {...props}></Icon>
