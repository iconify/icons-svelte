<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu3v6tmeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="vu3v6tmeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:male" {...props}></Icon>
