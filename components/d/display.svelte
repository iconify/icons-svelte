<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/i89f99xzv.css';
import '../../css/k/krgim9y4j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqnHOcdqL"><g class="v3_i3wktz"><rect class="i89f99xzv"/><path class="krgim9y4j"/></g></mask></defs><path mask="url(#SVGqnHOcdqL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:display" {...props}></Icon>
