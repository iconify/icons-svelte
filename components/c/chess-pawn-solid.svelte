<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7hd_lbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l7hd_lbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chess-pawn-solid" {...props}></Icon>
