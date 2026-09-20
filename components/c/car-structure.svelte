<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r41yzwbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r41yzwbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:car-structure" {...props}></Icon>
