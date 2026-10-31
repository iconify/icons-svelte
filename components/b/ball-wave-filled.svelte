<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsbbbdb0k.css';
import '../../css/w/w6m22iv5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsbbbdb0k"/><path clip-rule="evenodd" class="w6m22iv5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ball-wave-filled" {...props}></Icon>
