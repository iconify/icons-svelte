<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/lo2azab8w.css';
import '../../css/s/swzcsov6m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAOTGHdEW"><g class="v3_i3wktz"><path class="lo2azab8w"/><path class="swzcsov6m"/></g></mask></defs><path mask="url(#SVGAOTGHdEW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:blackboard" {...props}></Icon>
