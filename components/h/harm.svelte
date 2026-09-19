<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/q/qvlv7ibpn.css';
import '../../css/z/z_nh5vzzq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2zh71bzI"><g class="ufeehvblu"><path class="qvlv7ibpn"/><path class="z_nh5vzzq"/></g></mask></defs><path mask="url(#SVG2zh71bzI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:harm" {...props}></Icon>
