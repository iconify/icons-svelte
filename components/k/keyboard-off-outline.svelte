<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrii360xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrii360xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-off-outline" {...props}></Icon>
