<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/d9ti0tfzb.css';
import '../../css/w/wjxv5acdy.css';
import '../../css/z/zd3-8ac-t.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPAt0feET"><g class="v3_i3wktz"><path class="d9ti0tfzb"/><path class="wjxv5acdy"/><path clip-rule="evenodd" class="zd3-8ac-t"/></g></mask></defs><path mask="url(#SVGPAt0feET)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:group" {...props}></Icon>
