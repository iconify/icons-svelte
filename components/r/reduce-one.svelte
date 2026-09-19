<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/n/nx026r26k.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhkw6JehA"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="nx026r26k"/></g></mask></defs><path mask="url(#SVGhkw6JehA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:reduce-one" {...props}></Icon>
