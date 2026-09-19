<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5oymtkop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5oymtkop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:check-circle" {...props}></Icon>
