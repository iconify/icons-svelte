<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lchpdvb_j.css';
import '../../css/s/sigei6ulc.css';
import '../../css/y/yfk_enb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lchpdvb_j"/><path class="sigei6ulc"/><path class="yfk_enb6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-check-duotone" {...props}></Icon>
