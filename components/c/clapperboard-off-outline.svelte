<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg21u9l_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg21u9l_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clapperboard-off-outline" {...props}></Icon>
