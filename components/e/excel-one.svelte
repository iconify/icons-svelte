<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/x/xcc5o-bxz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqAlXveXc"><g class="s9cl3zbei"><rect class="g47cb4b4t"/><path class="xcc5o-bxz"/></g></mask></defs><path mask="url(#SVGqAlXveXc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:excel-one" {...props}></Icon>
