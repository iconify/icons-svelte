<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvzcewbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mvzcewbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:photo-camera" {...props}></Icon>
