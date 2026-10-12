<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqu_dzbcq.css';
import '../../css/d/dvq72viog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqu_dzbcq"/><path class="dvq72viog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carton-off-filled" {...props}></Icon>
