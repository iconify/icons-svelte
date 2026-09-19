<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm7opcb8n.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkrBqIdmR"><path class="hm7opcb8n"/></mask></defs><path mask="url(#SVGkrBqIdmR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bad" {...props}></Icon>
