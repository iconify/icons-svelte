<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drgbd2w6h.css';
import '../../css/c/c3_ibvh4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drgbd2w6h"/><path class="c3_ibvh4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-chevrons-down" {...props}></Icon>
