<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u21cuog4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u21cuog4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-stop" {...props}></Icon>
