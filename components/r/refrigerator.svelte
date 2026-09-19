<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pfnw24b8z.css';
import '../../css/b/bjd584byl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9wDgcdeE"><g class="v3_i3wktz"><rect class="pfnw24b8z"/><path class="bjd584byl"/></g></mask></defs><path mask="url(#SVG9wDgcdeE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:refrigerator" {...props}></Icon>
