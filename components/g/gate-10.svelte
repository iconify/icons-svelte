<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnnov91gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="xnnov91gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:gate-10" {...props}></Icon>
