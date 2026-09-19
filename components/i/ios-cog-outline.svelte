<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptj_bibnz.css';
import '../../css/z/z37-xpb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptj_bibnz"/><path class="z37-xpb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cog-outline" {...props}></Icon>
