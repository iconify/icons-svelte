<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy2k3-b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy2k3-b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-unknown" {...props}></Icon>
