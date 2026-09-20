<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xob65pb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xob65pb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flash-camera" {...props}></Icon>
