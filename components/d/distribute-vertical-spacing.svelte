<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/t/taetgzrim.css';
import '../../css/i/i2innpbyc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGw2JMGVNV"><g class="hv130ab-t"><path class="taetgzrim"/><path class="i2innpbyc"/></g></mask></defs><path mask="url(#SVGw2JMGVNV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:distribute-vertical-spacing" {...props}></Icon>
