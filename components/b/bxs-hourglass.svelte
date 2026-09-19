<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acnjw_bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acnjw_bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hourglass" {...props}></Icon>
