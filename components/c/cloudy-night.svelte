<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/l6-wjzcgj.css';
import '../../css/v/vlmdq3b3u.css';
import '../../css/p/pv14qwbuv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGd5BrMcQr"><g class="v3_i3wktz"><path class="l6-wjzcgj"/><path class="vlmdq3b3u"/><path class="pv14qwbuv"/></g></mask></defs><path mask="url(#SVGd5BrMcQr)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:cloudy-night" {...props}></Icon>
