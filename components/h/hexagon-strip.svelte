<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa_is4bzp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNCVvQcbr"><path class="aa_is4bzp"/></mask></defs><path mask="url(#SVGNCVvQcbr)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hexagon-strip" {...props}></Icon>
