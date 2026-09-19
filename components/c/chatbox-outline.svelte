<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ygl7brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-ygl7brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chatbox-outline" {...props}></Icon>
