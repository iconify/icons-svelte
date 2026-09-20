<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grcapebcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="grcapebcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:arrow-right-outline" {...props}></Icon>
