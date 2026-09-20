<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szrrrdbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szrrrdbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fingerprint" {...props}></Icon>
