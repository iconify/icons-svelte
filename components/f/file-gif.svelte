<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/my50xkbpo.css';
import '../../css/n/niqzbij3h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2vP1RcVR"><g class="v3_i3wktz"><path class="my50xkbpo"/><path class="niqzbij3h"/></g></mask></defs><path mask="url(#SVG2vP1RcVR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:file-gif" {...props}></Icon>
