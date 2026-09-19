<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/injpc11dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="injpc11dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:gripper-dots-vertical" {...props}></Icon>
