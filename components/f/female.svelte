<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h4iej7x0c.css';
import '../../css/o/ogc7ubbfh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGXrPvbdT"><g class="v3_i3wktz"><path class="h4iej7x0c"/><path class="ogc7ubbfh"/></g></mask></defs><path mask="url(#SVGGXrPvbdT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:female" {...props}></Icon>
