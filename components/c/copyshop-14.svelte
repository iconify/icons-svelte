<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u__94wbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u__94wbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:copyshop-14" {...props}></Icon>
