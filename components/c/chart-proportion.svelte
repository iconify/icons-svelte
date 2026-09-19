<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kb3w1gazs.css';
import '../../css/b/b0al4ebio.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8CB7dcHl"><g class="v3_i3wktz"><path class="kb3w1gazs"/><path class="b0al4ebio"/></g></mask></defs><path mask="url(#SVG8CB7dcHl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:chart-proportion" {...props}></Icon>
