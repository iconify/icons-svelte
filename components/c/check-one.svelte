<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/udz-79kzq.css';
import '../../css/p/pa9_zrbsc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIQLGgV2F"><g class="ufeehvblu"><path class="udz-79kzq"/><path class="pa9_zrbsc"/></g></mask></defs><path mask="url(#SVGIQLGgV2F)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:check-one" {...props}></Icon>
