<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yismpnbbv.css';
import '../../css/t/t3kg4fp0h.css';
import '../../css/z/zc_h-6bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path class="t3kg4fp0h"/><path class="zc_h-6bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-plus-filled" {...props}></Icon>
