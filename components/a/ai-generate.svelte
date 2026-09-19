<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg1d_jgxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg1d_jgxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-generate" {...props}></Icon>
