<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sywh_d5sb.css';
import '../../css/u/uidlf3bnh.css';
import '../../css/h/het1cerok.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1gk2AcMZ"><g class="ft5dv1b6b"><path class="sywh_d5sb"/><path class="uidlf3bnh"/><path class="het1cerok"/></g></mask></defs><path mask="url(#SVG1gk2AcMZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:recent-views-sort" {...props}></Icon>
