<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgxkgcndv.css';
import '../../css/e/e5703z3pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgxkgcndv"/><path class="e5703z3pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:map-pin" {...props}></Icon>
