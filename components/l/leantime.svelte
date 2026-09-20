<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c737xob8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c737xob8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:leantime" {...props}></Icon>
