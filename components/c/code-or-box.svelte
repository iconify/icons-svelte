<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp2qudbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2qudbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-or-box" {...props}></Icon>
