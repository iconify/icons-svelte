<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv-wqkbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lv-wqkbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bluesky-light" {...props}></Icon>
