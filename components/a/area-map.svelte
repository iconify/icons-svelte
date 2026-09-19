<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/g6ovlz6dh.css';
import '../../css/g/gazpy_epd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwOZAOeIa"><g class="aql7dnt-u"><path class="g6ovlz6dh"/><path class="gazpy_epd"/></g></mask></defs><path mask="url(#SVGwOZAOeIa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:area-map" {...props}></Icon>
