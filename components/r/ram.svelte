<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj9vgb4-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hj9vgb4-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ram" {...props}></Icon>
