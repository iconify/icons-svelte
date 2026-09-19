<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/enuncybsk.css';
import '../../css/h/hyr8-8bhd.css';
import '../../css/h/ha34b3bre.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRcYkvdtK"><g class="v3_i3wktz"><path class="enuncybsk"/><path class="hyr8-8bhd"/><path class="ha34b3bre"/></g></mask></defs><path mask="url(#SVGRcYkvdtK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:multi-function-knife" {...props}></Icon>
