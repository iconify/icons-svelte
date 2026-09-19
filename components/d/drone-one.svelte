<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/zxrl963_d.css';
import '../../css/k/k10hx2qog.css';
import '../../css/o/oaclm4ghi.css';
import '../../css/b/b_zoysbpp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvXdlvc7u"><g class="v3_i3wktz"><path class="zxrl963_d"/><path class="k10hx2qog"/><path class="oaclm4ghi"/><path class="b_zoysbpp"/></g></mask></defs><path mask="url(#SVGvXdlvc7u)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:drone-one" {...props}></Icon>
