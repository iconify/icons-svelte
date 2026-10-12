<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s9bcybcxn.css';
import '../../css/g/g5o4zccob.css';
import '../../css/f/f39w6ibxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s9bcybcxn"/><rect transform="rotate(90 19 19)" class="g5o4zccob"/><path class="f39w6ibxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chess-rook" {...props}></Icon>
