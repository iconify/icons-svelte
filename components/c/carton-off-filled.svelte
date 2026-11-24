<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uno68zbmk.css';
import '../../css/d/dvq72viog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uno68zbmk"/><path class="dvq72viog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carton-off-filled" {...props}></Icon>
