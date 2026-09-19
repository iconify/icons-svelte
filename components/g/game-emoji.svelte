<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6srddc_x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkvkc1cLV"><path class="d6srddc_x"/></mask></defs><path mask="url(#SVGkvkc1cLV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:game-emoji" {...props}></Icon>
