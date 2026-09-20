<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3l75_b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3l75_b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-integral-filled" {...props}></Icon>
