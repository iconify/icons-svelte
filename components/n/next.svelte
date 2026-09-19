<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni3z4obtq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmxdwiM4T"><path clip-rule="evenodd" class="ni3z4obtq"/></mask></defs><path mask="url(#SVGmxdwiM4T)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:next" {...props}></Icon>
