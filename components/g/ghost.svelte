<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/cf1w4fbaw.css';
import '../../css/r/rpgbrbc4i.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGln6CWcqi"><g class="v3_i3wktz"><path class="cf1w4fbaw"/><path class="rpgbrbc4i"/></g></mask></defs><path mask="url(#SVGln6CWcqi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ghost" {...props}></Icon>
