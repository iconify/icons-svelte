<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri43c8k7n.css';
import '../../css/z/z2f80nbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri43c8k7n"/><path class="z2f80nbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-up-line" {...props}></Icon>
