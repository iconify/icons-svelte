<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tst2p8buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tst2p8buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flag-off" {...props}></Icon>
