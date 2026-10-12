<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0v99vl1w.css';
import '../../css/p/pt9q_ib8s.css';
import '../../css/t/tqgpg9bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0v99vl1w"/><path class="pt9q_ib8s"/><path class="tqgpg9bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fish-off-filled" {...props}></Icon>
