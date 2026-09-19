<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0uz5ld-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0uz5ld-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ball-glow" {...props}></Icon>
