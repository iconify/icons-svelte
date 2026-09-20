<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrt76sboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrt76sboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-70-bluetooth" {...props}></Icon>
