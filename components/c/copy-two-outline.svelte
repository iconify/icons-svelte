<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiazg2b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wiazg2b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:copy-two-outline" {...props}></Icon>
