<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/it-6pnb9s.css';
import '../../css/e/eggrvn9ds.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSAcBcIzw"><g class="v3_i3wktz"><path class="it-6pnb9s"/><path class="eggrvn9ds"/></g></mask></defs><path mask="url(#SVGSAcBcIzw)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:connection-point-two" {...props}></Icon>
