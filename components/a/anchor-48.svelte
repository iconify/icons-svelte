<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru3berbsx.css';
import '../../css/x/x0sa_-lyq.css';
import '../../css/b/bd4fsf3wr.css';
import '../../css/k/koiau4b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ru3berbsx"/><path class="x0sa_-lyq"/><path class="bd4fsf3wr"/><path class="koiau4b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anchor-48" {...props}></Icon>
