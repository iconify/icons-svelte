<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bd8ephb8q.css';
import '../../css/g/gwpoo533p.css';
import '../../css/u/u65--k4ig.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGks21oeDl"><g class="ufeehvblu"><path class="bd8ephb8q"/><path class="gwpoo533p"/><path class="u65--k4ig"/></g></mask></defs><path mask="url(#SVGks21oeDl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:beer-mug" {...props}></Icon>
