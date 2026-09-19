<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2_bfiwax.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtHWbAZui"><path class="a2_bfiwax"/></mask></defs><path mask="url(#SVGtHWbAZui)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:mitsubishi" {...props}></Icon>
