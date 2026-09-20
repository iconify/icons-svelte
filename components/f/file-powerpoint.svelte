<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bre_3u76o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bre_3u76o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-powerpoint" {...props}></Icon>
