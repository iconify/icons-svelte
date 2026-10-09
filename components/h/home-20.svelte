<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g52ib27ry.css';
import '../../css/w/wno856buj.css';
import '../../css/d/dsaf1skdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g52ib27ry"/><path class="wno856buj"/><path class="dsaf1skdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-20" {...props}></Icon>
