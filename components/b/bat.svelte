<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0_m-9bfs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzYmnGefN"><path class="n0_m-9bfs"/></mask></defs><path mask="url(#SVGzYmnGefN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bat" {...props}></Icon>
