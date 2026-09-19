<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk68y1fno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bk68y1fno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coal-wagon" {...props}></Icon>
