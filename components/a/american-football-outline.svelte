<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4asfxowo.css';
import '../../css/x/xqkp-ixqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse transform="rotate(-45 256 256.002)" class="p4asfxowo"/><path class="xqkp-ixqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:american-football-outline" {...props}></Icon>
