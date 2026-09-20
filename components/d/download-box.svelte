<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg-6e0eht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg-6e0eht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:download-box" {...props}></Icon>
