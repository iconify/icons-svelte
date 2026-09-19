<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqwivf2fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vqwivf2fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:octogonal-eye" {...props}></Icon>
