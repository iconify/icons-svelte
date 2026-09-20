<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyl85rbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xyl85rbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-2018-light" {...props}></Icon>
