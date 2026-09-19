<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xikc5lbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xikc5lbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:coin-dollar" {...props}></Icon>
