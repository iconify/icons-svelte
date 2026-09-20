<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu4d6vbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wu4d6vbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:archive-solid" {...props}></Icon>
