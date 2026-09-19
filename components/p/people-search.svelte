<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kznc4_ijf.css';
import '../../css/b/b-i2hybmk.css';
import '../../css/i/ishhajbev.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGBrYLcER"><g class="v3_i3wktz"><path class="kznc4_ijf"/><path class="b-i2hybmk"/><path class="ishhajbev"/></g></mask></defs><path mask="url(#SVGGBrYLcER)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:people-search" {...props}></Icon>
