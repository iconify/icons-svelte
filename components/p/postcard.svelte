<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paaeio2fp.css';
import '../../css/r/rx4b74v7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="paaeio2fp"/><path class="rx4b74v7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:postcard" {...props}></Icon>
