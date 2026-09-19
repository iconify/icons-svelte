<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6h2mp5hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="t6h2mp5hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-left-square" {...props}></Icon>
