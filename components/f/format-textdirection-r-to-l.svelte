<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay4kt0lor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="ay4kt0lor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-textdirection-r-to-l" {...props}></Icon>
