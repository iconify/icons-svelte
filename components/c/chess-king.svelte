<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sw65xgb3l.css';
import '../../css/g/g5o4zccob.css';
import '../../css/s/sko61s_um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sw65xgb3l"/><rect transform="rotate(90 19 19)" class="g5o4zccob"/><path class="sko61s_um"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chess-king" {...props}></Icon>
