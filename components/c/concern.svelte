<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csw0kbbpv.css';
import '../../css/l/lt9927b3v.css';
import '../../css/w/ws63ig51q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGl4rQrcUi"><g class="csw0kbbpv"><path class="lt9927b3v"/><path class="ws63ig51q"/></g></mask></defs><path mask="url(#SVGl4rQrcUi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:concern" {...props}></Icon>
