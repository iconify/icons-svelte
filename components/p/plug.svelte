<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kkd09i5ve.css';
import '../../css/o/o2jheybdw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGonZNscbv"><g class="v3_i3wktz"><path class="kkd09i5ve"/><path class="o2jheybdw"/></g></mask></defs><path mask="url(#SVGonZNscbv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:plug" {...props}></Icon>
