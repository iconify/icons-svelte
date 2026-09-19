<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz9gp_bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oz9gp_bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rolling-dice-cup" {...props}></Icon>
