<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksnh2ccrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksnh2ccrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boxing-gloves" {...props}></Icon>
