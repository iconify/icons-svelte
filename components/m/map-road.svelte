<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/e/eo3-_3b1e.css';
import '../../css/f/f6z86b9cg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGM9RU2R1h"><g class="ufeehvblu"><path class="eo3-_3b1e"/><path class="f6z86b9cg"/></g></mask></defs><path mask="url(#SVGM9RU2R1h)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:map-road" {...props}></Icon>
