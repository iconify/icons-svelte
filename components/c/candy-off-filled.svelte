<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyv0rce4w.css';
import '../../css/m/m5_8ni9aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyv0rce4w"/><path class="m5_8ni9aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:candy-off-filled" {...props}></Icon>
