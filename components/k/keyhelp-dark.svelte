<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz3u5f60f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xz3u5f60f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:keyhelp-dark" {...props}></Icon>
