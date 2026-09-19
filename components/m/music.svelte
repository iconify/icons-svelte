<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd_80beog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bd_80beog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:music" {...props}></Icon>
