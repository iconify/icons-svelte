<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asui5acag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="asui5acag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:one-pip" {...props}></Icon>
