<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b13lxxb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="b13lxxb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-forwarded" {...props}></Icon>
