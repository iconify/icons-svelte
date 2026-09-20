<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvcv351wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pvcv351wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-and-taxi-checkerboard" {...props}></Icon>
