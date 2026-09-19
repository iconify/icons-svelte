<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/che1mymjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="che1mymjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-left" {...props}></Icon>
