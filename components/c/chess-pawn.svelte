<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/km-s25uct.css';
import '../../css/g/g5o4zccob.css';
import '../../css/z/zrb5eurrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="km-s25uct"/><rect transform="rotate(90 19 19)" class="g5o4zccob"/><path class="zrb5eurrl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chess-pawn" {...props}></Icon>
