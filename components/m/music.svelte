<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xa2d9bb0k.css';
import '../../css/j/jroqwgjpq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLiEztcGW"><g class="v3_i3wktz"><path class="xa2d9bb0k"/><path class="jroqwgjpq"/></g></mask></defs><path mask="url(#SVGLiEztcGW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:music" {...props}></Icon>
