<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pjch7lbxz.css';
import '../../css/c/cj2g5-b5u.css';
import '../../css/p/p4i9s3b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pjch7lbxz"/><path class="cj2g5-b5u"/><path clip-rule="evenodd" class="p4i9s3b2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ratio-duotone" {...props}></Icon>
