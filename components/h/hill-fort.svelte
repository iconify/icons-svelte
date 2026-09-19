<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0m8mmivq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q0m8mmivq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hill-fort" {...props}></Icon>
