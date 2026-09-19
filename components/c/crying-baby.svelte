<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/t66yi6bna.css';
import '../../css/m/mhsmvbuqt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgbmeKdJf"><g class="v3_i3wktz"><path class="t66yi6bna"/><path class="mhsmvbuqt"/></g></mask></defs><path mask="url(#SVGgbmeKdJf)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:crying-baby" {...props}></Icon>
