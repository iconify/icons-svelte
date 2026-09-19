<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pstg2i40z.css';
import '../../css/r/r3j7g_mer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pstg2i40z"/><path class="r3j7g_mer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-wink-tongue" {...props}></Icon>
