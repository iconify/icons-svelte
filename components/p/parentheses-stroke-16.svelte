<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsp1_aclb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xsp1_aclb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:parentheses-stroke-16" {...props}></Icon>
