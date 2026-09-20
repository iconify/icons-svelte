<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuq106bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nuq106bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fork-crossing-knife" {...props}></Icon>
