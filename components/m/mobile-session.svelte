<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viyk3hb3u.css';
import '../../css/r/rqvdmjbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="viyk3hb3u"/><path class="rqvdmjbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-session" {...props}></Icon>
