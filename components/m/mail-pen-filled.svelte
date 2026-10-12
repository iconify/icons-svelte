<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy1isrbes.css';
import '../../css/z/zrmu6-ymm.css';
import '../../css/z/zc_h-6bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy1isrbes"/><path class="zrmu6-ymm"/><path class="zc_h-6bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-pen-filled" {...props}></Icon>
