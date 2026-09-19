<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lto4ctpit.css';
import '../../css/h/h-keftbiv.css';
import '../../css/z/z3ko96b0e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeSYLeVnl"><g class="ufeehvblu"><path class="lto4ctpit"/><path clip-rule="evenodd" class="h-keftbiv"/><path class="z3ko96b0e"/></g></mask></defs><path mask="url(#SVGeSYLeVnl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:monitor" {...props}></Icon>
