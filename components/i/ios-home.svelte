<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etxzxd_fz.css';
import '../../css/e/ezvo8ibdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etxzxd_fz"/><path class="ezvo8ibdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-home" {...props}></Icon>
