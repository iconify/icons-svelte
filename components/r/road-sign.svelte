<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/r-3ti3tas.css';
import '../../css/v/v7tv4gjxm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6G40NcYd"><g class="v3_i3wktz"><path class="r-3ti3tas"/><path class="v7tv4gjxm"/></g></mask></defs><path mask="url(#SVG6G40NcYd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:road-sign" {...props}></Icon>
