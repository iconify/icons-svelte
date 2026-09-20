<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmos9kbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmos9kbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-border" {...props}></Icon>
