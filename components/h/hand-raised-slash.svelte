<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_xk6kb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u_xk6kb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hand-raised-slash" {...props}></Icon>
