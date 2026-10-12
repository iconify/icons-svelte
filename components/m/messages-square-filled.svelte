<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa4i_ynuq.css';
import '../../css/q/qfxk42bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa4i_ynuq"/><path class="qfxk42bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:messages-square-filled" {...props}></Icon>
