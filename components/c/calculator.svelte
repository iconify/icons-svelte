<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wr9hafbnl.css';
import '../../css/r/rjaer0dlx.css';
import '../../css/f/f8pnpzbfo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHl06vcSf"><g class="ufeehvblu"><path class="wr9hafbnl"/><path class="rjaer0dlx"/><path class="f8pnpzbfo"/></g></mask></defs><path mask="url(#SVGHl06vcSf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:calculator" {...props}></Icon>
