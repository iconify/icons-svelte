<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm31a9pfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="cm31a9pfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chess-pawn" {...props}></Icon>
