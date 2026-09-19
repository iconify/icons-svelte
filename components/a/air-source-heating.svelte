<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbl-03cst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbl-03cst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:air-source-heating" {...props}></Icon>
