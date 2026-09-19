<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lku1cybne.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5D2dBcbR"><path class="lku1cybne"/></mask></defs><path mask="url(#SVG5D2dBcbR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bad-two" {...props}></Icon>
