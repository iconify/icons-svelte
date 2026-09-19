<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/n/nfwguf0bv.css';
import '../../css/j/jry5s1b0c.css';
import '../../css/q/qup_wkbsi.css';
import '../../css/j/jwr8zqbox.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCcPLPbGL"><g class="hv130ab-t"><path class="nfwguf0bv"/><path class="jry5s1b0c"/><path class="qup_wkbsi"/><path class="jwr8zqbox"/></g></mask></defs><path mask="url(#SVGCcPLPbGL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:radish" {...props}></Icon>
