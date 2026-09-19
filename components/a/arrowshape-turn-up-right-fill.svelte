<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_bfxb-og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="d_bfxb-og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowshape-turn-up-right-fill" {...props}></Icon>
