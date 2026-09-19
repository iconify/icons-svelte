<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohtjlzb9o.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWbHkneAU"><path class="ohtjlzb9o"/></mask></defs><path mask="url(#SVGWbHkneAU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:game-two" {...props}></Icon>
