<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zscbcbv9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zscbcbv9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:minus-circled" {...props}></Icon>
