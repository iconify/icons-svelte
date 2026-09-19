<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp-xl0bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tp-xl0bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:empty-hourglass" {...props}></Icon>
