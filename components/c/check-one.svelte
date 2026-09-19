<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qkvyde2_l.css';
import '../../css/h/h13c8cb6j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBM25vJeV"><g class="v3_i3wktz"><path class="qkvyde2_l"/><path class="h13c8cb6j"/></g></mask></defs><path mask="url(#SVGBM25vJeV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:check-one" {...props}></Icon>
