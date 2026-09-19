<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd21t8b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fd21t8b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-game-controller-a" {...props}></Icon>
