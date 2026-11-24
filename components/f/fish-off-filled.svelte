<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv7ro-bzc.css';
import '../../css/l/lru0_snsm.css';
import '../../css/t/tqgpg9bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bv7ro-bzc"/><path class="lru0_snsm"/><path class="tqgpg9bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fish-off-filled" {...props}></Icon>
