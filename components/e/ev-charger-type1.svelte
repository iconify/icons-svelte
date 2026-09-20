<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr6iflb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr6iflb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ev-charger-type1" {...props}></Icon>
