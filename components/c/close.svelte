<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgj5nhvcz.css';
import '../../css/m/mjyk0m7ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="bgj5nhvcz"/><path class="mjyk0m7ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:close" {...props}></Icon>
