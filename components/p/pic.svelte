<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x9u4gylcp.css';
import '../../css/i/ixqdcsbvp.css';
import '../../css/x/x6bijybfe.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGh2FVndaf"><g class="v3_i3wktz"><path clip-rule="evenodd" class="x9u4gylcp"/><path clip-rule="evenodd" class="ixqdcsbvp"/><path class="x6bijybfe"/></g></mask></defs><path mask="url(#SVGh2FVndaf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pic" {...props}></Icon>
