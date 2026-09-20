<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrcm38g4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yrcm38g4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-dancing-with-sparkles" {...props}></Icon>
