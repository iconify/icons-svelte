<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bcqa_q4nr.css';
import '../../css/m/mh64p_bcl.css';
import '../../css/n/na8ucjw-y.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaOxgXc8s"><g class="ufeehvblu"><path class="bcqa_q4nr"/><path class="mh64p_bcl"/><path class="na8ucjw-y"/></g></mask></defs><path mask="url(#SVGaOxgXc8s)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:folder-close" {...props}></Icon>
