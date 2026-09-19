<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/b6m-fgjan.css';
import '../../css/f/flmqy2bwe.css';
import '../../css/t/t0i7idwtd.css';
import '../../css/t/t0_em0bkz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGe315J8GG"><g class="v3_i3wktz"><path class="b6m-fgjan"/><path class="flmqy2bwe"/><path class="t0i7idwtd"/><path class="t0_em0bkz"/></g></mask></defs><path mask="url(#SVGe315J8GG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:radar-chart" {...props}></Icon>
