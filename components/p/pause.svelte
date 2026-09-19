<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srwnm0noq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="srwnm0noq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pause" {...props}></Icon>
