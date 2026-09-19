<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhjb4mbgw.css';
import '../../css/v/vv_2udbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xhjb4mbgw"/><path class="vv_2udbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ansible" {...props}></Icon>
