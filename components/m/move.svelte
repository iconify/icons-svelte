<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlo_a2b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zlo_a2b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:move" {...props}></Icon>
