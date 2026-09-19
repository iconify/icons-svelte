<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3xgr0b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3xgr0b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:floor-hatch" {...props}></Icon>
