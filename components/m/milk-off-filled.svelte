<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvw8s9b2p.css';
import '../../css/q/qq2gd69ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yvw8s9b2p"/><path class="qq2gd69ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:milk-off-filled" {...props}></Icon>
