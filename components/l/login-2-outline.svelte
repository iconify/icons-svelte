<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olusrszwm.css';
import '../../css/j/j-an33b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olusrszwm"/><path class="j-an33b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:login-2-outline" {...props}></Icon>
