<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggfdt95ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ggfdt95ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:rew" {...props}></Icon>
