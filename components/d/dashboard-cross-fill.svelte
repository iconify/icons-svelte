<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh79fpdwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh79fpdwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-cross-fill" {...props}></Icon>
