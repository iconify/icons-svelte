<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af4cuy1nq.css';
import '../../css/q/qghtzzbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af4cuy1nq"/><path class="qghtzzbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:emoji-hand-cheers" {...props}></Icon>
