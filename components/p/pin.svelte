<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8jsn2i4o.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEpqjdbuG"><path class="e8jsn2i4o"/></mask></defs><path mask="url(#SVGEpqjdbuG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pin" {...props}></Icon>
