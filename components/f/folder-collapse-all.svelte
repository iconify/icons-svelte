<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewdzdgb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ewdzdgb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-collapse-all" {...props}></Icon>
