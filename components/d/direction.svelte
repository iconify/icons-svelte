<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r5ke29wou.css';
import '../../css/k/kw5sjshgk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGuvfmNtB"><g class="ft5dv1b6b"><rect class="r5ke29wou"/><path class="kw5sjshgk"/></g></mask></defs><path mask="url(#SVGGuvfmNtB)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:direction" {...props}></Icon>
