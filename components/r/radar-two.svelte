<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/p/pohjlbb7n.css';
import '../../css/g/g0mjuxxff.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTzCynSAx"><g class="aql7dnt-u"><path class="pohjlbb7n"/><path clip-rule="evenodd" class="g0mjuxxff"/></g></mask></defs><path mask="url(#SVGTzCynSAx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:radar-two" {...props}></Icon>
