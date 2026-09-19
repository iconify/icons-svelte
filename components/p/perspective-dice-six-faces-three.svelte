<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx5zfftik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx5zfftik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-six-faces-three" {...props}></Icon>
