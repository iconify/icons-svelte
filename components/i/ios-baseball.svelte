<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udcbvob3v.css';
import '../../css/l/l_nfrbb_z.css';
import '../../css/r/r-n9oxbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udcbvob3v"/><path class="l_nfrbb_z"/><path class="r-n9oxbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-baseball" {...props}></Icon>
