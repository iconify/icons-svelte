<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql44vfbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql44vfbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-mic" {...props}></Icon>
