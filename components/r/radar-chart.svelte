<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wvdu4-vmy.css';
import '../../css/h/hny_tqt2a.css';
import '../../css/h/h6jcxqydj.css';
import '../../css/k/k6zktqb0a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCaLLJb2l"><g class="ufeehvblu"><path class="wvdu4-vmy"/><path class="hny_tqt2a"/><path class="h6jcxqydj"/><path class="k6zktqb0a"/></g></mask></defs><path mask="url(#SVGCaLLJb2l)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:radar-chart" {...props}></Icon>
