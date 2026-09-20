<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp5rksb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp5rksb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-panel" {...props}></Icon>
