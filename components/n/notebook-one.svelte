<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/r/r2i0scb_x.css';
import '../../css/o/oymgzybxy.css';
import '../../css/l/l5ay6cc6w.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvIAeWcvK"><g class="ufeehvblu"><path class="r2i0scb_x"/><path class="oymgzybxy"/><path class="l5ay6cc6w"/></g></mask></defs><path mask="url(#SVGvIAeWcvK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:notebook-one" {...props}></Icon>
