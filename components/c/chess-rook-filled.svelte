<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxq05gomn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxq05gomn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chess-rook-filled" {...props}></Icon>
