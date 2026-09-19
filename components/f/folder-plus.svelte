<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/msv6_bc6s.css';
import '../../css/q/q3jhrhbxa.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDMRtDeyg"><g class="s9cl3zbei"><path class="msv6_bc6s"/><path class="q3jhrhbxa"/></g></mask></defs><path mask="url(#SVGDMRtDeyg)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:folder-plus" {...props}></Icon>
