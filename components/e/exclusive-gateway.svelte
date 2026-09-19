<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/ez330t4ze.css';
import '../../css/h/h5g3_-b7x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG11V2DcGG"><g class="s9cl3zbei"><path class="ez330t4ze"/><path class="h5g3_-b7x"/></g></mask></defs><path mask="url(#SVG11V2DcGG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:exclusive-gateway" {...props}></Icon>
