<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/ucv-pibjs.css';
import '../../css/c/co9te6vwq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdKRUdeVA"><g class="ufeehvblu"><path class="ucv-pibjs"/><path class="co9te6vwq"/></g></mask></defs><path mask="url(#SVGdKRUdeVA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:local-two" {...props}></Icon>
