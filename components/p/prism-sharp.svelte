<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woxu74yrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="woxu74yrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:prism-sharp" {...props}></Icon>
