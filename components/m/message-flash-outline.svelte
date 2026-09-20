<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szvk_z3ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szvk_z3ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-flash-outline" {...props}></Icon>
