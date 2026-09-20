<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xphyfpx8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xphyfpx8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:farm-home" {...props}></Icon>
