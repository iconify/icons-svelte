<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kid9qfb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kid9qfb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-4-hearts" {...props}></Icon>
