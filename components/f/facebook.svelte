<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va4l-rdig.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfIrXF2an"><path class="va4l-rdig"/></mask></defs><path mask="url(#SVGfIrXF2an)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:facebook" {...props}></Icon>
