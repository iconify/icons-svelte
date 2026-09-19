<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/p/pvg15bqqz.css';
import '../../css/p/p2i7mob5a.css';
import '../../css/c/cl5y_sbef.css';
import '../../css/g/gcg1107xt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxv1c7yjn"><g class="ufeehvblu"><path class="pvg15bqqz"/><path class="p2i7mob5a"/><path class="cl5y_sbef"/><path class="gcg1107xt"/></g></mask></defs><path mask="url(#SVGxv1c7yjn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:devices" {...props}></Icon>
