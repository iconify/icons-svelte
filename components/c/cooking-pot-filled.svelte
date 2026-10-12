<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_88a0exd.css';
import '../../css/n/np_ttjutp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_88a0exd"/><path clip-rule="evenodd" class="np_ttjutp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cooking-pot-filled" {...props}></Icon>
