<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/t/tridcqbpp.css';
import '../../css/c/cxgs_geig.css';
import '../../css/x/xz56qgbdb.css';
import '../../css/u/u-38-obdd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiS12mctT"><g class="ufeehvblu"><path class="tridcqbpp"/><path class="cxgs_geig"/><path class="xz56qgbdb"/><path class="u-38-obdd"/></g></mask></defs><path mask="url(#SVGiS12mctT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:plug" {...props}></Icon>
