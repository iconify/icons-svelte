<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/rm2v37f1t.css';
import '../../css/h/h39g81kyw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUQZeRbnh"><g class="v3_i3wktz"><rect class="rm2v37f1t"/><path class="h39g81kyw"/></g></mask></defs><path mask="url(#SVGUQZeRbnh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:lock" {...props}></Icon>
