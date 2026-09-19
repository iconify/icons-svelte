<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxjr0wsud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxjr0wsud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:power-generator" {...props}></Icon>
