<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sthnq_bas.css';
import '../../css/r/rm7c5vbvg.css';
import '../../css/d/dawzjdknl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sthnq_bas"/><path class="rm7c5vbvg"/><path class="dawzjdknl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cast-filled" {...props}></Icon>
