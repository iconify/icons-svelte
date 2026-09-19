<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-ud_9n5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-ud_9n5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battle-axe" {...props}></Icon>
