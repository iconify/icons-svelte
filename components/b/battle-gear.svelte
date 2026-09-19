<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6c1dbcal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6c1dbcal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battle-gear" {...props}></Icon>
