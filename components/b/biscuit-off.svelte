<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yel296gpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yel296gpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:biscuit-off" {...props}></Icon>
