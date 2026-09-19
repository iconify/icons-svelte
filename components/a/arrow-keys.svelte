<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tr_c1_8xr.css';
import '../../css/e/e-57amjqa.css';
import '../../css/u/uyzfr2hik.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTlTMCQ1H"><g class="ft5dv1b6b"><path class="tr_c1_8xr"/><path class="e-57amjqa"/><path class="uyzfr2hik"/></g></mask></defs><path mask="url(#SVGTlTMCQ1H)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:arrow-keys" {...props}></Icon>
