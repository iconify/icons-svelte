<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd1vp8bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd1vp8bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chess-gloss" {...props}></Icon>
