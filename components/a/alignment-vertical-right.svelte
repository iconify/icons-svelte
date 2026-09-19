<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/l/l8x7f9b9k.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHL01ablt"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="l8x7f9b9k"/></g></mask></defs><path mask="url(#SVGHL01ablt)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:alignment-vertical-right" {...props}></Icon>
