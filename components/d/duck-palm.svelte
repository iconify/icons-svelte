<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow16voj6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow16voj6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:duck-palm" {...props}></Icon>
