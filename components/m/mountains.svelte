<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-jd13bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-jd13bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mountains" {...props}></Icon>
