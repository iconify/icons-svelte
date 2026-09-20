<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7fgytnir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b7fgytnir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bridge-shape-horizontal" {...props}></Icon>
