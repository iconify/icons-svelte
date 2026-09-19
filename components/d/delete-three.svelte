<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mzszod_2j.css';
import '../../css/q/ql5u_n4hs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7Sv5okMa"><g class="s9cl3zbei"><circle class="mzszod_2j"/><path class="ql5u_n4hs"/></g></mask></defs><path mask="url(#SVG7Sv5okMa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:delete-three" {...props}></Icon>
