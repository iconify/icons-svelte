<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/ez330t4ze.css';
import '../../css/l/lqkoj1b-f.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGO3Wn5cUT"><g class="s9cl3zbei"><path class="ez330t4ze"/><path class="lqkoj1b-f"/></g></mask></defs><path mask="url(#SVGO3Wn5cUT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:parallel-gateway" {...props}></Icon>
