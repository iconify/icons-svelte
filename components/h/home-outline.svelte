<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4tob8bkg.css';
import '../../css/p/p4bqiyolx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w4tob8bkg"/><path class="p4bqiyolx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:home-outline" {...props}></Icon>
