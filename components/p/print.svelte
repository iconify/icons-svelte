<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys2v17h9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ys2v17h9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:print" {...props}></Icon>
