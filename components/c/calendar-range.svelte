<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yif2k3mfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yif2k3mfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-range" {...props}></Icon>
