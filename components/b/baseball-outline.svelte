<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fb195ladc.css';
import '../../css/d/d-047h7xd.css';
import '../../css/c/cvqkf_yxp.css';
import '../../css/l/ly-3bkb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fb195ladc"/><path clip-rule="evenodd" class="d-047h7xd"/><path class="cvqkf_yxp"/><path clip-rule="evenodd" class="ly-3bkb4n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:baseball-outline" {...props}></Icon>
