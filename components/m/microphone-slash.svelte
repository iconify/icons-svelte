<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeaudz1zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xeaudz1zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:microphone-slash" {...props}></Icon>
