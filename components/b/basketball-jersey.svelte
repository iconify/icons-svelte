<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr4g3w4iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zr4g3w4iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:basketball-jersey" {...props}></Icon>
