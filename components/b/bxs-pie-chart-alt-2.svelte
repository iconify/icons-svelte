<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc_sw6bwg.css';
import '../../css/r/ro-axhb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc_sw6bwg"/><path class="ro-axhb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-pie-chart-alt-2" {...props}></Icon>
