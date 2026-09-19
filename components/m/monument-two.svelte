<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j9hg1or3h.css';
import '../../css/h/hn8ry4rfn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbvjRecWc"><g class="v3_i3wktz"><path class="j9hg1or3h"/><path class="hn8ry4rfn"/></g></mask></defs><path mask="url(#SVGbvjRecWc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:monument-two" {...props}></Icon>
