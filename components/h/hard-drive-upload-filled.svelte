<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg_u039uv.css';
import '../../css/e/e2m_lkbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hg_u039uv"/><path class="e2m_lkbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hard-drive-upload-filled" {...props}></Icon>
