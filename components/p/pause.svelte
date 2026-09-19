<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcx3l54-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="pcx3l54-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:pause" {...props}></Icon>
