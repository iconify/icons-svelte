<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udl05cesy.css';
import '../../css/r/r2agu4stc.css';
import '../../css/d/dmah2_beo.css';
import '../../css/f/fprc9_bni.css';
import '../../css/v/vthft9fin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udl05cesy"/><path class="r2agu4stc"/><path class="dmah2_beo"/><path class="fprc9_bni"/><path class="vthft9fin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-rainy" {...props}></Icon>
