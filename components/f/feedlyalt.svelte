<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf2iorbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="yf2iorbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:feedlyalt" {...props}></Icon>
