<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_n7fwc3g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpLVWObsf"><path class="l_n7fwc3g"/></mask></defs><path mask="url(#SVGpLVWObsf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:align-vertical-center-two" {...props}></Icon>
