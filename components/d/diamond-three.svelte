<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh5my5ilm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1xKdadUH"><path class="rh5my5ilm"/></mask></defs><path mask="url(#SVG1xKdadUH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:diamond-three" {...props}></Icon>
