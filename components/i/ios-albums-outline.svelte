<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muygl9lui.css';
import '../../css/r/rg45nfbgg.css';
import '../../css/a/aaogj5ntx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="muygl9lui"/><path class="rg45nfbgg"/><path class="aaogj5ntx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-albums-outline" {...props}></Icon>
