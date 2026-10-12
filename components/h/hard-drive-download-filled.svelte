<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg_u039uv.css';
import '../../css/e/e0kfvbb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hg_u039uv"/><path class="e0kfvbb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hard-drive-download-filled" {...props}></Icon>
