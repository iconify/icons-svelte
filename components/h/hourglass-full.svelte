<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bt97avbye.css';
import '../../css/w/wdtytfyie.css';
import '../../css/r/r045luk3o.css';
import '../../css/j/jftmc7bxv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNJJcMcWx"><g class="ufeehvblu"><path class="bt97avbye"/><path class="wdtytfyie"/><path class="r045luk3o"/><path class="jftmc7bxv"/></g></mask></defs><path mask="url(#SVGNJJcMcWx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:hourglass-full" {...props}></Icon>
