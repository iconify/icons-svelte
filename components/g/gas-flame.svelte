<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgouwr_ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tgouwr_ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gas-flame" {...props}></Icon>
