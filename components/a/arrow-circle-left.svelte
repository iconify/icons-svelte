<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1whaobfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i1whaobfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-circle-left" {...props}></Icon>
