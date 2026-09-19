<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/i/i5p4ugbzq.css';
import '../../css/m/m297d4evg.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCmuUndfN"><g class="gopnm44um"><rect class="i5p4ugbzq"/><path class="m297d4evg"/></g></mask></defs><path mask="url(#SVGCmuUndfN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:alignment-bottom-right" {...props}></Icon>
