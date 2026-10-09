<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is7w60blm.css';
import '../../css/s/sb8adabhc.css';
import '../../css/u/u9pq35-6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="is7w60blm"/><path class="sb8adabhc"/><path class="u9pq35-6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-plus-20-bold" {...props}></Icon>
