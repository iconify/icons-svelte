<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehaaoiotd.css';
import '../../css/z/zf2tkskut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehaaoiotd"/><path class="zf2tkskut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pen-tool-filled" {...props}></Icon>
