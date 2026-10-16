<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql0y1hb7o.css';
import '../../css/d/dscdkvbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ql0y1hb7o"/><path class="dscdkvbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lock-20-bold" {...props}></Icon>
