<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/c/c0fhn_bpl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNCVIAbII"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="c0fhn_bpl"/></g></mask></defs><path mask="url(#SVGNCVIAbII)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:reduce-one" {...props}></Icon>
