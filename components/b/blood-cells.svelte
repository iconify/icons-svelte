<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyawl_bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gyawl_bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:blood-cells" {...props}></Icon>
