<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgoppkbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vgoppkbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-down-left" {...props}></Icon>
