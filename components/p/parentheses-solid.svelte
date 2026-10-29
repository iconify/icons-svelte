<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmafvfbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmafvfbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:parentheses-solid" {...props}></Icon>
