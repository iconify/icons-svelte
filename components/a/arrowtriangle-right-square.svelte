<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4vt97b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u4vt97b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-right-square" {...props}></Icon>
