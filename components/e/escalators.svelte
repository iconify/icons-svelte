<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/lfaqxlbsl.css';
import '../../css/m/mxqp5wvsi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgnWzveXa"><g class="aql7dnt-u"><path class="lfaqxlbsl"/><path class="mxqp5wvsi"/></g></mask></defs><path mask="url(#SVGgnWzveXa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:escalators" {...props}></Icon>
