<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud9cl0y3d.css';
import '../../css/a/aba_xubdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud9cl0y3d"/><path class="aba_xubdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-dot-filled" {...props}></Icon>
