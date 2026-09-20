<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd00cbc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nd00cbc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-arrow-bottom-left" {...props}></Icon>
