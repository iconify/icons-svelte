<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu9k0z8qm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAZIpbcqT"><path class="tu9k0z8qm"/></mask></defs><path mask="url(#SVGAZIpbcqT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:diamond-two" {...props}></Icon>
