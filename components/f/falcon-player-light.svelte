<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc9w6xbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zc9w6xbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:falcon-player-light" {...props}></Icon>
