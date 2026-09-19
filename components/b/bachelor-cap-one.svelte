<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/ph1wei72v.css';
import '../../css/v/vwunhkbts.css';
import '../../css/g/g5flyubde.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8K0cLdxT"><g class="v3_i3wktz"><path class="ph1wei72v"/><path class="vwunhkbts"/><path class="g5flyubde"/></g></mask></defs><path mask="url(#SVG8K0cLdxT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bachelor-cap-one" {...props}></Icon>
