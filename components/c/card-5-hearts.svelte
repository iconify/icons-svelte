<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptvz3z25y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptvz3z25y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-5-hearts" {...props}></Icon>
