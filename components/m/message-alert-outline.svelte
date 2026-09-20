<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhzx4obkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhzx4obkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-alert-outline" {...props}></Icon>
