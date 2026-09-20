<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph3u7ibzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ph3u7ibzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ethernet-port" {...props}></Icon>
