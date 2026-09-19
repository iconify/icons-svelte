<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1fdrv0xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1fdrv0xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-home" {...props}></Icon>
