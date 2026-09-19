<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/i/isa-krbuv.css';
import '../../css/c/cbfu_ebav.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5lr6Heij"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="isa-krbuv"/><path class="cbfu_ebav"/></g></mask></defs><path mask="url(#SVG5lr6Heij)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:messages" {...props}></Icon>
