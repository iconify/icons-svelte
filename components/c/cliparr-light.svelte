<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzi1mt9mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzi1mt9mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cliparr-light" {...props}></Icon>
