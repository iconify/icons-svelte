<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sywh_d5sb.css';
import '../../css/o/opzq61bog.css';
import '../../css/c/c0hz57d3e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJAPDIe8Z"><g class="ft5dv1b6b"><path class="sywh_d5sb"/><path class="opzq61bog"/><path class="c0hz57d3e"/></g></mask></defs><path mask="url(#SVGJAPDIe8Z)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:recent-views-sort" {...props}></Icon>
