<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_c634jky.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhhMGxOsy"><path class="h_c634jky"/></mask></defs><path mask="url(#SVGhhMGxOsy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pinwheel" {...props}></Icon>
