<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnm_4wbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnm_4wbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-pawn-fill" {...props}></Icon>
