<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/l0xa7qbsw.css';
import '../../css/g/g99d2gzfk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkgL0Mb5o"><g class="v3_i3wktz"><path class="l0xa7qbsw"/><path class="g99d2gzfk"/></g></mask></defs><path mask="url(#SVGkgL0Mb5o)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:mountain" {...props}></Icon>
