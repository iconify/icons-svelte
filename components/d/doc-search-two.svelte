<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o0ebj98gu.css';
import '../../css/j/jlin40zen.css';
import '../../css/n/nglwwbzdo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiChrWclO"><g class="ft5dv1b6b"><path class="o0ebj98gu"/><path class="jlin40zen"/><path class="nglwwbzdo"/></g></mask></defs><path mask="url(#SVGiChrWclO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:doc-search-two" {...props}></Icon>
