<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2-yyco-z.css';
import '../../css/c/ceoqrxlgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2-yyco-z"/><path class="ceoqrxlgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dollar-circle-stars" {...props}></Icon>
