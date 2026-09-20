<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sndodubfo.css';
import '../../css/a/a4nkfj3oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sndodubfo"/><path class="a4nkfj3oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpsysinfo-dark" {...props}></Icon>
