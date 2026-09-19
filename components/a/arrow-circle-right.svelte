<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/a/au3p78pym.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn7tnhdUJ"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="au3p78pym"/></g></mask></defs><path mask="url(#SVGn7tnhdUJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:arrow-circle-right" {...props}></Icon>
