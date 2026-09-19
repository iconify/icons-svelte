<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/s/sjxycbjzr.css';
import '../../css/x/xdjtwgb7o.css';
import '../../css/j/jbtaph4oz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlkr5ieYj"><g class="s9cl3zbei"><path class="sjxycbjzr"/><path class="xdjtwgb7o"/><path class="jbtaph4oz"/></g></mask></defs><path mask="url(#SVGlkr5ieYj)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:icecream-five" {...props}></Icon>
