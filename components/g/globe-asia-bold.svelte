<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lfdnlqvyw.css';
import '../../css/z/zzbol-1ap.css';
import '../../css/d/difx-7blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lfdnlqvyw"/><path clip-rule="evenodd" class="zzbol-1ap"/><path class="difx-7blb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-asia-bold" {...props}></Icon>
