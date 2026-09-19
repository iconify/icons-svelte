<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5x8xjbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5x8xjbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:oni" {...props}></Icon>
