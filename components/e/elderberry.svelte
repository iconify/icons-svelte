<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3j8hc2km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z3j8hc2km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:elderberry" {...props}></Icon>
