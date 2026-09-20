<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5stnbb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y5stnbb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cairn-and-tall-rectangle" {...props}></Icon>
