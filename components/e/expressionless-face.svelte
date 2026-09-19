<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/c/c6j5yyb2e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGil5VI8zv"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="c6j5yyb2e"/></g></mask></defs><path mask="url(#SVGil5VI8zv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:expressionless-face" {...props}></Icon>
