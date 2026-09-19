<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s19-dyb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s19-dyb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-arrow-dropright" {...props}></Icon>
