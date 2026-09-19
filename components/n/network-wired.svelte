<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iakv479-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="iakv479-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:network-wired" {...props}></Icon>
