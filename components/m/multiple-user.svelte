<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiek2ibjp.css';
import '../../css/t/tml6j6bpx.css';
import '../../css/c/ctqpb75vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aiek2ibjp"/><path class="tml6j6bpx"/><path class="ctqpb75vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:multiple-user" {...props}></Icon>
