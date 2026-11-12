<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm366-d-x.css';
import '../../css/j/jutyogb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wm366-d-x"/><path class="jutyogb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maildev-dark" {...props}></Icon>
