<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5s_hac7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x5s_hac7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:propane-tank" {...props}></Icon>
