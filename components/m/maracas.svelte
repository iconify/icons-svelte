<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byqln5o1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="byqln5o1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:maracas" {...props}></Icon>
