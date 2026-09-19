<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/d4oyb2wqm.css';
import '../../css/t/tx6iv9bwx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2McFke6e"><g class="v3_i3wktz"><path class="d4oyb2wqm"/><path class="tx6iv9bwx"/></g></mask></defs><path mask="url(#SVG2McFke6e)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:phone-outgoing" {...props}></Icon>
