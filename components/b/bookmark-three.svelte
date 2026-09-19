<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/ao9e7w7dq.css';
import '../../css/b/b3c2jhbey.css';
import '../../css/p/p_88yybnm.css';
import '../../css/q/qgwr9vbgn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcT46vdvh"><g class="v3_i3wktz"><path class="ao9e7w7dq"/><path class="b3c2jhbey"/><path class="p_88yybnm"/><path class="qgwr9vbgn"/></g></mask></defs><path mask="url(#SVGcT46vdvh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bookmark-three" {...props}></Icon>
