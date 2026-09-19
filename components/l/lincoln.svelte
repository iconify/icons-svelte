<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/u_yu_z0ri.css';
import '../../css/i/imnm-7_fw.css';
import '../../css/w/wd_ka24qp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMqVYreIW"><g class="s9cl3zbei"><path class="u_yu_z0ri"/><path class="imnm-7_fw"/><path class="wd_ka24qp"/></g></mask></defs><path mask="url(#SVGMqVYreIW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:lincoln" {...props}></Icon>
