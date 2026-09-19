<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo4xr7bel.css';
import '../../css/q/q4497hb1w.css';
import '../../css/s/s11q8obkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo4xr7bel"/><path class="q4497hb1w"/><path class="s11q8obkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-audible" {...props}></Icon>
