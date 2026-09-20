<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdezvif_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zdezvif_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:car-taxi-1-remix" {...props}></Icon>
