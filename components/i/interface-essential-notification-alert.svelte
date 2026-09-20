<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pno3q_b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pno3q_b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-notification-alert" {...props}></Icon>
