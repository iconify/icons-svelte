<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/h/hvpug8bzi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9BbMHtSG"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="hvpug8bzi"/></g></mask></defs><path mask="url(#SVG9BbMHtSG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:arrow-circle-up" {...props}></Icon>
