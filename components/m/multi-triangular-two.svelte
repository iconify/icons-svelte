<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/q-pan9bpu.css';
import '../../css/n/ni2kn61-e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNj5d8daY"><g class="aql7dnt-u"><path class="q-pan9bpu"/><path class="ni2kn61-e"/></g></mask></defs><path mask="url(#SVGNj5d8daY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:multi-triangular-two" {...props}></Icon>
