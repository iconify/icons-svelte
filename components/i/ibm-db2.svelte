<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z601nxboe.css';
import '../../css/s/sh51lircq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z601nxboe"/><path class="sh51lircq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-db2" {...props}></Icon>
