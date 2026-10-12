<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wexh7077m.css';
import '../../css/r/r1d07kbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wexh7077m"/><path class="r1d07kbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-pulse-filled" {...props}></Icon>
