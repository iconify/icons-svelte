<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym7f000we.css';
import '../../css/g/gv5ke9bho.css';
import '../../css/r/rqzve2bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym7f000we"/><path class="gv5ke9bho"/><path class="rqzve2bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:documents-minimalistic-bold" {...props}></Icon>
