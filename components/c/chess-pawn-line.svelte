<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-wwalx4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-wwalx4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-pawn-line" {...props}></Icon>
