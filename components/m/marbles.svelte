<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v125nobos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v125nobos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:marbles" {...props}></Icon>
