<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/btgc_sbaw.css';
import '../../css/m/mcinq7b2v.css';
import '../../css/y/yu0shrb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="btgc_sbaw"/><path class="mcinq7b2v"/><path class="yu0shrb5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:folder-check" {...props}></Icon>
