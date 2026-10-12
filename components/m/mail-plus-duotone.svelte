<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lchpdvb_j.css';
import '../../css/s/sigei6ulc.css';
import '../../css/g/g5ucz7ltn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lchpdvb_j"/><path class="sigei6ulc"/><path class="g5ucz7ltn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-plus-duotone" {...props}></Icon>
