<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhed42bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhed42bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-square-outline" {...props}></Icon>
