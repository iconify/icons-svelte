<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbswf2fdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vbswf2fdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:polygon" {...props}></Icon>
