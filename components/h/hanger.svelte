<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw8l6dbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sw8l6dbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hanger" {...props}></Icon>
