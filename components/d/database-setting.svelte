<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/lcee_744z.css';
import '../../css/q/quqne-byv.css';
import '../../css/q/qm1qe08zp.css';
import '../../css/z/zhs-pukwe.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3I1QMbiJ"><g class="aql7dnt-u"><path class="lcee_744z"/><path class="quqne-byv"/><path class="qm1qe08zp"/><path class="zhs-pukwe"/></g></mask></defs><path mask="url(#SVG3I1QMbiJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:database-setting" {...props}></Icon>
