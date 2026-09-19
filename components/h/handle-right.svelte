<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/v/vcum2uxal.css';
import '../../css/o/odgo2qjxq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGe5DFsbhx"><g class="ufeehvblu"><rect class="vcum2uxal"/><path class="odgo2qjxq"/></g></mask></defs><path mask="url(#SVGe5DFsbhx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:handle-right" {...props}></Icon>
