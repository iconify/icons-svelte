<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oel34lrcl.css';
import '../../css/l/l4y1h7b8q.css';
import '../../css/q/qug4cqf0k.css';
import '../../css/z/z_ar8h2tr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpXjuwbUV"><g class="ufeehvblu"><path class="oel34lrcl"/><path class="l4y1h7b8q"/><path class="qug4cqf0k"/><path class="z_ar8h2tr"/></g></mask></defs><path mask="url(#SVGpXjuwbUV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:fire-extinguisher-one" {...props}></Icon>
