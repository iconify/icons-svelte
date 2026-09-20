<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn4z0js2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zn4z0js2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-map-pin-with-dot" {...props}></Icon>
