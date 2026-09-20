<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okvzx3b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okvzx3b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flash-off-outline" {...props}></Icon>
