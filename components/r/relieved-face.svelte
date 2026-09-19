<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/y/ysq7ivk7x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUX7KqcvM"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="ysq7ivk7x"/></g></mask></defs><path mask="url(#SVGUX7KqcvM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:relieved-face" {...props}></Icon>
