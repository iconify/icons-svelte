<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dawklnb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dawklnb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-grab-remix" {...props}></Icon>
