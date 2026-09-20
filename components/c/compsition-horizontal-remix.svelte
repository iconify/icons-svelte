<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/matl_strt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="matl_strt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:compsition-horizontal-remix" {...props}></Icon>
