<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/h/h-jjnh20g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTSr2SKjh"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="h-jjnh20g"/></g></mask></defs><path mask="url(#SVGTSr2SKjh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:alignment-left-center" {...props}></Icon>
