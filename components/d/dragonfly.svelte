<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqrx59q5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqrx59q5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dragonfly" {...props}></Icon>
