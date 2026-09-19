<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/w/w_tvd7f2n.css';
import '../../css/s/sz1263boh.css';
import '../../css/o/ovzwzoprl.css';
import '../../css/e/euvpd1bsq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9HsJdEAE"><g class="v3_i3wktz"><path class="w_tvd7f2n"/><path class="sz1263boh"/><path class="ovzwzoprl"/><path class="euvpd1bsq"/></g></mask></defs><path mask="url(#SVG9HsJdEAE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:gift" {...props}></Icon>
