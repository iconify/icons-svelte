<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-eh3wbpz.css';
import '../../css/j/j-38zcbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-eh3wbpz"/><path class="j-38zcbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:node-red" {...props}></Icon>
