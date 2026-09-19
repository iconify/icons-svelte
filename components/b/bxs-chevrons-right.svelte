<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp7_n3beu.css';
import '../../css/b/bxv5csb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp7_n3beu"/><path class="bxv5csb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevrons-right" {...props}></Icon>
