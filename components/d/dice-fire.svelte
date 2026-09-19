<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib_cetbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ib_cetbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dice-fire" {...props}></Icon>
