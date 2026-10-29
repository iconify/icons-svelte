<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvh9a2pzk.css';
import '../../css/h/hgwnlybsl.css';
import '../../css/e/e_2p_w-co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvh9a2pzk"/><path class="hgwnlybsl"/><path class="e_2p_w-co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:inbox" {...props}></Icon>
