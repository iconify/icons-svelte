<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/r/rbb69cszp.css';
import '../../css/b/bd4pvgbwl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9gDKKegE"><g class="aql7dnt-u"><circle class="rbb69cszp"/><path class="bd4pvgbwl"/></g></mask></defs><path mask="url(#SVG9gDKKegE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:diamond-ring" {...props}></Icon>
