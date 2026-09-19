<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2w1ue3kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="l2w1ue3kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:battery-3" {...props}></Icon>
