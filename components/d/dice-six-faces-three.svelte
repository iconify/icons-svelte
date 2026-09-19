<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrcn_602m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mrcn_602m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-six-faces-three" {...props}></Icon>
