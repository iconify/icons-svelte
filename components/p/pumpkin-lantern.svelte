<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8s-p2b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b8s-p2b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pumpkin-lantern" {...props}></Icon>
