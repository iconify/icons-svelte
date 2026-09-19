<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up_ycpgrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="up_ycpgrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bridge" {...props}></Icon>
