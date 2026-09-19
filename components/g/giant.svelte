<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkky4_b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zkky4_b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:giant" {...props}></Icon>
