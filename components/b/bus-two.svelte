<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/l/ld34ikbzm.css';
import '../../css/d/dn67aubms.css';
import '../../css/v/v2_52rrfv.css';
import '../../css/i/ii0u8bc6s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQakfndGH"><g class="wwvp95byt"><path clip-rule="evenodd" class="ld34ikbzm"/><path class="dn67aubms"/><path class="v2_52rrfv"/><path class="ii0u8bc6s"/></g></mask></defs><path mask="url(#SVGQakfndGH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bus-two" {...props}></Icon>
