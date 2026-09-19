<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/s-kistkta.css';
import '../../css/u/u-8_srfhg.css';
import '../../css/h/hv9f26_mj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXL1SydBb"><g class="ufeehvblu"><path class="s-kistkta"/><path class="u-8_srfhg"/><path class="hv9f26_mj"/></g></mask></defs><path mask="url(#SVGXL1SydBb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:delete-five" {...props}></Icon>
