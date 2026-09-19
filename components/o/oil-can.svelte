<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwn4_kbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="lwn4_kbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:oil-can" {...props}></Icon>
