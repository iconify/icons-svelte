<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpctkhcgf.css';
import '../../css/c/cpnat3u3d.css';
import '../../css/b/b14djybkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":402,"height":100};
const content = `<path clip-rule="evenodd" class="xpctkhcgf"/><path class="cpnat3u3d"/><path class="b14djybkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mage-ai" {...props}></Icon>
