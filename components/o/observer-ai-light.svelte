<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xted9krxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xted9krxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:observer-ai-light" {...props}></Icon>
