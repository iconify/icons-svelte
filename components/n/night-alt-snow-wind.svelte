<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzn_di5ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="zzn_di5ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-alt-snow-wind" {...props}></Icon>
