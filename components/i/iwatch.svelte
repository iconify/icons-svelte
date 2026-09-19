<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/i/iquwcyt8f.css';
import '../../css/d/d3sptcc3n.css';
import '../../css/d/dcn00fqin.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkG8fWc7K"><g class="s9cl3zbei"><path class="iquwcyt8f"/><path class="d3sptcc3n"/><path class="dcn00fqin"/></g></mask></defs><path mask="url(#SVGkG8fWc7K)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:iwatch" {...props}></Icon>
