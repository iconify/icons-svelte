<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy4t3zb5c.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMPVN8ciM"><path class="iy4t3zb5c"/></mask></defs><path mask="url(#SVGMPVN8ciM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bridge-one" {...props}></Icon>
