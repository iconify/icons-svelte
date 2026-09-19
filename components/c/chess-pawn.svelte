<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_59zsbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="t_59zsbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:chess-pawn" {...props}></Icon>
