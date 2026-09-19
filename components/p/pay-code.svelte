<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fqzg-n1xw.css';
import '../../css/i/ixe451mff.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZeL81xTZ"><g class="v3_i3wktz"><path class="fqzg-n1xw"/><path class="ixe451mff"/></g></mask></defs><path mask="url(#SVGZeL81xTZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pay-code" {...props}></Icon>
