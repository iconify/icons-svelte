<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev134hbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ev134hbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-nodes" {...props}></Icon>
