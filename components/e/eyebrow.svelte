<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/b/b8jxfhb0t.css';
import '../../css/k/k-eaexmhb.css';
import '../../css/n/nxtfqrbmx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNrGRWdta"><g class="ufeehvblu"><path class="b8jxfhb0t"/><path class="k-eaexmhb"/><path class="nxtfqrbmx"/></g></mask></defs><path mask="url(#SVGNrGRWdta)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:eyebrow" {...props}></Icon>
