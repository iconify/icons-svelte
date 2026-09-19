<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxz985mfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxz985mfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chess-pawn-filled" {...props}></Icon>
