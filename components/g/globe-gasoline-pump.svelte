<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbau5pxqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mbau5pxqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:globe-gasoline-pump" {...props}></Icon>
