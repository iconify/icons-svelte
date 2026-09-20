<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bimt6g92e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bimt6g92e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:geyser-from-ground" {...props}></Icon>
