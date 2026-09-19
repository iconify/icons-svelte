<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/k/kmydzbsxv.css';
import '../../css/b/bk8ioe9xt.css';
import '../../css/a/a1ppbdbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="kmydzbsxv"/><circle class="bk8ioe9xt"/><path class="a1ppbdbvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:court" {...props}></Icon>
