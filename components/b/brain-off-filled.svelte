<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp4eihbdx.css';
import '../../css/v/vox3mdpjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hp4eihbdx"/><path class="vox3mdpjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brain-off-filled" {...props}></Icon>
