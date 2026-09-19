<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmee-3b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nmee-3b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cactus-pot" {...props}></Icon>
