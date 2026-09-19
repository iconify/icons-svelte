<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq_3h82mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lq_3h82mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-hangout" {...props}></Icon>
