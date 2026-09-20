<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akkw_4bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="akkw_4bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:icicles" {...props}></Icon>
