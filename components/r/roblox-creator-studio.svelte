<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq1zcxy1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vq1zcxy1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:roblox-creator-studio" {...props}></Icon>
