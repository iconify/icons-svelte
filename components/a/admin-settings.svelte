<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3v2hfb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s3v2hfb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-settings" {...props}></Icon>
