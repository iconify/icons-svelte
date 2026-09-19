<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_6b1qb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_6b1qb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chainsaw" {...props}></Icon>
