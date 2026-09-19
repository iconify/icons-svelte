<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bisr4s8em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bisr4s8em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:poncho" {...props}></Icon>
