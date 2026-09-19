<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r-kk51bsn.css';
import '../../css/a/asbi-uwfa.css';
import '../../css/d/deju6fb9n.css';
import '../../css/x/xjd58kxuc.css';
import '../../css/h/h33ui5bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="r-kk51bsn"/><path clip-rule="evenodd" class="asbi-uwfa"/><path class="deju6fb9n"/><path clip-rule="evenodd" class="xjd58kxuc"/><path class="h33ui5bld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-tears-outline" {...props}></Icon>
