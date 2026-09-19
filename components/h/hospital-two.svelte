<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/sco-lqgta.css';
import '../../css/n/ny92e0b3s.css';
import '../../css/d/d3lktyezi.css';
import '../../css/s/s8xi34pba.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQMriXbAv"><g class="aql7dnt-u"><path class="sco-lqgta"/><path class="ny92e0b3s"/><path class="d3lktyezi"/><path class="s8xi34pba"/></g></mask></defs><path mask="url(#SVGQMriXbAv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hospital-two" {...props}></Icon>
