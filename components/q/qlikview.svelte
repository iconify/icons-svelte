<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm2_ybbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xm2_ybbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:qlikview" {...props}></Icon>
