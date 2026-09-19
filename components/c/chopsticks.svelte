<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v819-jb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v819-jb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chopsticks" {...props}></Icon>
