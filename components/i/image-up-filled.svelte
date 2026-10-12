<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnu5vacfx.css';
import '../../css/q/qcetc5ipd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnu5vacfx"/><path clip-rule="evenodd" class="qcetc5ipd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-up-filled" {...props}></Icon>
