<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzmit6bbq.css';
import '../../css/v/vwdgxlbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzmit6bbq"/><path class="vwdgxlbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-layer-plus" {...props}></Icon>
