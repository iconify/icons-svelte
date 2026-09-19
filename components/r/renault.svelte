<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vey1dxbgo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpGmnzbRE"><path class="vey1dxbgo"/></mask></defs><path mask="url(#SVGpGmnzbRE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:renault" {...props}></Icon>
