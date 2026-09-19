<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz2fdxb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cz2fdxb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:claw" {...props}></Icon>
