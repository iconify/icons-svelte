<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7om0018w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a7om0018w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ball-heart" {...props}></Icon>
