<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz13vkbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lz13vkbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nametag-light" {...props}></Icon>
