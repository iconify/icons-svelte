<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnh2cebyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnh2cebyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-1-duotone" {...props}></Icon>
