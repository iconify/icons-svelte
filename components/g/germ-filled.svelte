<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg86vcuii.css';
import '../../css/v/vypii6bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg86vcuii"/><path clip-rule="evenodd" class="vypii6bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:germ-filled" {...props}></Icon>
