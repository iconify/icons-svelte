<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mi53ns-dt.css';
import '../../css/w/w-web3b5l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtDPMgbrM"><g class="aql7dnt-u"><path class="mi53ns-dt"/><path class="w-web3b5l"/></g></mask></defs><path mask="url(#SVGtDPMgbrM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bloom" {...props}></Icon>
