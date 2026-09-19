<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1nxs9bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="p1nxs9bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:question" {...props}></Icon>
