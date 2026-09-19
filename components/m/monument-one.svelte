<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/r_e0x_bru.css';
import '../../css/k/kkorzz3fw.css';
import '../../css/j/j9hg1or3h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUL5lIbwM"><g class="v3_i3wktz"><path class="r_e0x_bru"/><path class="kkorzz3fw"/><path class="j9hg1or3h"/></g></mask></defs><path mask="url(#SVGUL5lIbwM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:monument-one" {...props}></Icon>
