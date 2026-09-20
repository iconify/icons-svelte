<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igpqev6sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="igpqev6sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grin-tongue-wink-solid" {...props}></Icon>
