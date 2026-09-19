<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj5m3bbfz.css';
import '../../css/z/ziaiz_9lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tj5m3bbfz"/><path class="ziaiz_9lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-skip-back-outline" {...props}></Icon>
