<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/m/mtj6u6nhh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGij5x3ViN"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="mtj6u6nhh"/></g></mask></defs><path mask="url(#SVGij5x3ViN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:alignment-left-top" {...props}></Icon>
