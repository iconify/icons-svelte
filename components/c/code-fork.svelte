<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2hu5m5ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r2hu5m5ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:code-fork" {...props}></Icon>
