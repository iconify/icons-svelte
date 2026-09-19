<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msplu1c3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="msplu1c3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plane-departure" {...props}></Icon>
