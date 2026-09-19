<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c5szvdnvs.css';
import '../../css/d/ddymbxshg.css';
import '../../css/n/nwj63hb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c5szvdnvs"/><path class="ddymbxshg"/><path class="nwj63hb-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:edit-outline" {...props}></Icon>
