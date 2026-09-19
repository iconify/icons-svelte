<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntk5uyc5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntk5uyc5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:adobe-xd" {...props}></Icon>
