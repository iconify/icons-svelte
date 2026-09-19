<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg7r2pbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gg7r2pbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:almond" {...props}></Icon>
