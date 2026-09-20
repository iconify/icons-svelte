<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etn01zbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="etn01zbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-stop-filled" {...props}></Icon>
