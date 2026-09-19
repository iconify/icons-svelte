<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brsyw1b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brsyw1b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:box-trap" {...props}></Icon>
