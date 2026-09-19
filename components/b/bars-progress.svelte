<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xru7odbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xru7odbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bars-progress" {...props}></Icon>
