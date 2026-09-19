<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhy94o1ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhy94o1ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chess-pawn" {...props}></Icon>
