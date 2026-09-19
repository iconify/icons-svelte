<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz5v9-vqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mz5v9-vqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flaming-arrow" {...props}></Icon>
