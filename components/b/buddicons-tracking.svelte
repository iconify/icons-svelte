<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjdajlbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xjdajlbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-tracking" {...props}></Icon>
