<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyo_37bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="uyo_37bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chevron-left" {...props}></Icon>
