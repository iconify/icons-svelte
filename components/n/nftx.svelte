<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyjy3kbll.css';
import '../../css/p/p_067m8_e.css';
import '../../css/v/va1a_7b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyjy3kbll"/><path class="p_067m8_e"/><path class="va1a_7b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nftx" {...props}></Icon>
