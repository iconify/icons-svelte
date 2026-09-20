<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gguz8nb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gguz8nb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:charging-station-with-bolt" {...props}></Icon>
